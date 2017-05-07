# Docs

Documentacão para o projeto microservicer

# Servicos

Para essa parte inicial do projeto sera necessario um conjunto de servcicos desctrito aboixo

## Secão
* [Query](https://github.com/alexcvcoelho-gabrielgio/session-query)
* [Command](https://github.com/alexcvcoelho-gabrielgio/session-command)
* [Worker](https://github.com/alexcvcoelho-gabrielgio/session-worker)

## Rastreamento

* [Query](https://github.com/alexcvcoelho-gabrielgio/track-query)
* [Command](https://github.com/alexcvcoelho-gabrielgio/track-command)
* [Worker](https://github.com/alexcvcoelho-gabrielgio/track-worker)

## Simulacao
* [Sim](https://github.com/alexcvcoelho-gabrielgio/sim-worker)

# Modelos

Definicao generica dos modelos que serao utizados entres os servidos.

## session
```clojure
{ 
  :brand String ;;marca do carro
  :model String ;; modelo
  :hdId String ;; alguma forma de indetificacao unica do carro
}
```

## action
```clojure
{
  :action String ;; acao que vai ser broadcasted
  :session-id Obejct ;; id da session
}
```

## track-item
```clojure
{
  :loc ;;localicao do item
      {
        :lat Double ;;latitude 
        :long Double ;;longitude
      }
  :vel Double ;;valocidade do carro
  :gas-lvl Double ;; nivel da casolina
}
```

## Commands e Query
Essa documentacao sera gerada pelo swagger-ui, em breve.

