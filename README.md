# shelf_graphql

Middleware do Shelf para servidor graphql.

# Especificação da linguagem

Graphql utiliza uma linguagem de Query para realizar as consultas.
Cabe ao servidor interpretar e retornar a solicitação pedida pelo usuário.
A específicação da linguagem está disponível [nesse link](https://spec.graphql.org/).

ex:
```graphql
mutation {
  likeStory(storyID: 12345) {
    story {
      likeCount
    }
  }
}
```

# Arquitetura

- [Documentação de arquitetura](ARCHITECTURE.md).

# Servidores graphql de outras linguagens

- [Apollo Server (Javascript)](https://www.apollographql.com/docs/apollo-server/).
- [graphql_server (Dart)](https://pub.dev/packages/graphql_server2).


