# OpenAPI Specification for the Xero Accounting API
[![Build Status](https://travis-ci.org/admo26/xero-accounting.svg?branch=master)](https://travis-ci.org/admo26/xero-accounting)

## Viewing the specification
You can view the spec using the following links:
- SwaggerUI: https://admo26.github.io/openapi/swagger-ui/
- ReDoc: https://admo26.github.io/openapi/
- Look full spec:
    + JSON https://admo26.github.io/openapi/swagger.json
    + YAML https://admo26.github.io/openapi/swagger.yaml
- Preview spec version for branch `[branch]`: https://admo26.github.io/openapi/preview/[branch]

Thanks to the [Rebilly](https://github.com/Rebilly) team for sharing their [generator-openapi-repo](https://github.com/Rebilly/generator-openapi-repo) project and making this really easy.

## Working on the specification
If you find any issues with the spec :open_mouth: feel free to send us a pull request. You can make the changes in your favourite OpenAPI editor or clone this repo to run Swagger Editor locally.
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and `cd`
    + Run `npm install`

### Usage

1. Run `npm start`
2. Checkout console output to see where local server is started. You can use all [links](#links) (except `preview`) by replacing https://admo26.github.io/xero-accounting/ with url from the message: `Server started <url>`
3. Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
4. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
**TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
5. Once you finish with the changes you can run tests using: `npm test`
6. Share you changes with the rest of the world by pushing to GitHub :smile:
