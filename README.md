# @x12i/mdreports-types usage example

Shared Zod schemas and TypeScript types for Markdown Reports Studio.

This consuming application demonstrates **validate incoming json and report contract errors** using the published npm package, pinned to `0.4.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- Validate a Markdown Reports request against the shared schema.
- Share template and render-response contracts across the service and its client.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/mdreports-types)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
