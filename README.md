# NodeJS Express Application Using OpenAPI Generator

## Technologies

[OpenAPI Generator](https://openapi-generator.tech/)

[NodeJS Express Server](https://expressjs.com/en/starter/hello-world.html)

## Initial Setup

The `contract.json` file is used as our OpenAPI contract. The OpenAPI contract was created with [APIcurio](https://www.apicur.io/studio/) and downloaded.

This application was initially created using the `nodejs-express-server` generator, with the following command:

``` shell
npx @openapitools/openapi-generator-cli  generate -i contract.json -g nodejs-express-server
```
