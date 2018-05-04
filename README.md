# apollo-basic-server

## Run

(Node >= 8.5)

```
npm i
npm start
```

## With a client

Repo: [https://github.com/cedric25/vue-apollo-app](https://github.com/cedric25/vue-apollo-app)

## More

Server code coming from apollographql.com > [Quick Start](https://www.apollographql.com/docs/apollo-server/example.html)

Two endpoints get exposed:

`/graphql` > Main GraphQL endpoint

`/graphiql` > Living documentation

Only valid query:
```graphql
query {
  books {
    title
    author
  }
}
```
