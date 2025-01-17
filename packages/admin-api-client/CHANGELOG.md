# @shopify/admin-api-client

## 0.2.2

### Patch Changes

- b2414c2f: Remove `Partial` around the `ClientResponse.data` type for easier consumption of the client's returned typed data
- Updated dependencies [b2414c2f]
  - @shopify/graphql-client@0.9.2

## 0.2.1

### Patch Changes

- Updated dependencies [a23cd941]
  - @shopify/graphql-client@0.9.1

## 0.2.0

### Minor Changes

- 0286e7fe: Export a REST API client from `admin-api-client`, with an API that is similar to the GraphQL client.
- 18781092: Updated shopify-api GraphQL clients' APIs to be closer to the underlying clients
- 2b9e06f6: Add the raw network response object to `ResponseErrors`
- 194ddcf2: Update api version validation error, generic error messages and client types
- c9622cd7: Update `UNSUPPORTED_API_VERSION` log type to `Unsupported_Api_Version` for consistent log type format

### Patch Changes

- 88858305: Fixed an issue with the `require` path being incorrect in package.json.
- 218f4521: Use the new GraphQL API clients in shopify-api to use all of the latest features, including automatic types for query / mutation return object and variables.

  For more information and examples, see the [migration guide to v9](https://github.com/Shopify/shopify-api-js/blob/main/packages/shopify-api/docs/migrating-to-v9.md#using-the-new-clients).

- Updated dependencies [218f4521]
- Updated dependencies [49952d66]
- Updated dependencies [0286e7fe]
- Updated dependencies [18781092]
- Updated dependencies [2b9e06f6]
- Updated dependencies [194ddcf2]
- Updated dependencies [c9622cd7]
- Updated dependencies [82ee942e]
  - @shopify/graphql-client@0.9.0

## 0.1.0

### Minor Changes

- ca89ef06: Added the ability to automatically type GraphQL queries to the Storefront API when the files created by @shopify/api-codegen-preset are loaded for the app.
- ef053fa5: Added the ability to automatically type GraphQL queries when the files created by @shopify/api-codegen-preset are loaded for the app.

### Patch Changes

- Updated dependencies [ca89ef06]
- Updated dependencies [ef053fa5]
- Updated dependencies [49d5966e]
  - @shopify/graphql-client@0.8.0
