# Reproducer for Issue 464

This is a minimal reproducer for [#464](https://github.com/camunda/camunda-8-js-sdk/issues/464).

To run: 

- `npm i`
- `bun index.ts`

Observe expected error: 

`error: Missing required configuration CAMUNDA_OAUTH_URL. Please supply this value as an environment variable or configuration object field.`

- `source test.env`
- `bun index.ts`

No error is emitted.