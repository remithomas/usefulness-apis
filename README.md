# Usefulness APIs

## What and Why ?

An _usefulness_ API is an API with some basic (important) features, like `user connexion`, `setted database` and `Docker` ready. Every projects *have to* be developped in _TDD_.

It's like a boilerplate to set up a project quickly.

## Features

- User connexion/registration
- Using a database with migration possibilities
- Docker ready
- A dev environment already configured (editor, lint, travis, code coverage)

### Development features

A great and flexible development environnement is important. It's important also to quickly integrate other developers.
When manage database, it should be easier to handle database migrations.

### User features

The main feature is user connexion and ability to register some new user. This should create authentication using tokens.

### Deploiement features

Docker or _container_ solutions are great to allow you flexibility and speed when you deploy your apps.

## Contributions

Never hesitate to contribute to the follow repositories. Submit _issues_, _comments_ and _PRs_ !
You can also create your own repositories. To create a better _usefulness API_, you ~should~ have to develop in [TDD](https://en.wikipedia.org/wiki/Test_driven_development).

## Projects (created and planned)

### Elixir

- usefulness-api-phoenix

### NodeJS

- [usefulness-api-expressjs](https://github.com/remithomas/usefulness-api-expressjs)
- usefulness-api-expressjs-reasonml

### PHP

- [usefulness-api-zf3](https://github.com/remithomas/usefulness-api-zf3) (not ready)
- usefulness-api-laravel

## How to avoid Useful _mess_ ?

- Just _Pull Request_ never _ninja merge_ or whatever solutions you did to quick fix any _mess_ or dev. You should create only one commit per feature, that's the reason you have to create a _PR_ when adding your code with multiple commits. This allows you to get a clean history.
- Your commits should say something important.
- If you are using [Travis](https://travis-ci.org) always wait the green bullet, even if its' trivial, otherwise why use _travis_ ??