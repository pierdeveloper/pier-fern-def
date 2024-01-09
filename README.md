# Pier API

## What is in this repository?

This repository contains

- Pier's Fern API Definition which lives in the [definition](./fern/api/definition/) folder
- Generators (see [generators.yml](./fern/api/generators.yml))

## What is in the API Definition?

The API Definition contains information about what endpoints, types, and errors are used in the API. To make sure that the definition is valid, you can use the Fern CLI.

```bash
npm install -g fern-api # Installs CLI
fern check # Checks if the definition is valid
```

## What are generators?

Generators read in your API Definition and output artifacts. See [generators.yml](./fern/api/generators.yml).

To trigger the generators run:

```bash
fern generate
```

## Where are the docs?

- [Pier Fern Api Docs](https://pier.docs.buildwithfern.com/api-reference/)
    - This is what we will be showing customers in the future
- [Readme Api Docs](https://pier-dev.readme.io/reference/introduction)
    - Same docs as fern just different format
