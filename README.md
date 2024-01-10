# Pier API

## What is in this repository?

This repository contains

- Pier's Fern API Definition which lives in the [definition](./fern/definition/) folder
- Pier's Docs configuration which lives in the [docs](./fern/docs/) folder
- Generators for outputting a Postman collection or OpenAPI spec (see [generators.yml](./fern/generators.yml))

## What is in the API Definition?

The API Definition contains information about what endpoints, types, and errors are used in the API. To make sure that the definition is valid, you can use the Fern CLI.

```bash
npm install -g fern-api # Installs CLI
fern check # Checks if the definition is valid
```

## What are generators?

Generators read in your API Definition and output artifacts. See [generators.yml](./fern/generators.yml).

To trigger the generators run:

```bash
fern generate
```

The outputs will be available locally in the `./fern/generated` folder.
