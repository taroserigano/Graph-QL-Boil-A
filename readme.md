# GraphQL Boilerplate Project

A GraphQL boilerplate that supports GraphQL, subscriptions, and testing.


## Get Started

1. Clone the repo

2. Run `npm install`

3. Set up a config file. Here's an example for your dev and test environments.

```json
{
    "development": {
        "DATABASE_URL": "mongodb://localhost/graphql-blog-dev",
        "JWT_SECRET": "abc123098!!!"
    },
    "test": {
        "DATABASE_URL": "mongodb://localhost/graphql-blog-test",
        "JWT_SECRET": "abc123098!!!"
    }
}
```

4. Run `npm run dev` to start up the development environment

5. Head over to `localhost:3000` to make some GraphQL requests using GraphQL Playground

## Get Started with Tests

1. Run `npm test` to execute the jest test suite

## To Add

- [ ] Testing

