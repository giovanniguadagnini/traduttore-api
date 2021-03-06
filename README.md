# Traduttore OpenAPI Specification
[![Build Status](https://travis-ci.org/mbaezpy/traduttore-api.svg?branch=master)](https://travis-ci.org/mbaezpy/traduttore-api)

This repository contains the specification of the Traduttore API.
Follow the links to have access to the related resources.

## Resource Model 
A diagram illustrating the Resource model can be found in the figures folder.
To edit the file use http://draw.io


## Mock Server
A mock server running on the latest specification is deployed at:
https://traduttore-api.herokuapp.com/api/v1.0/

The mock server is hosted at: https://github.com/mbaezpy/traduttore-api-mock

## API Specification

- Documentation(ReDoc): https://mbaezpy.github.io/traduttore-api/
- SwaggerUI: https://mbaezpy.github.io/traduttore-api/swagger-ui/
- Look full spec:
    + JSON https://mbaezpy.github.io/traduttore-api/swagger.json
    + YAML https://mbaezpy.github.io/traduttore-api/swagger.yaml
- Preview spec version for branch `[branch]`: https://mbaezpy.github.io/traduttore-api/preview/[branch]

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and `cd`
    + Run `npm install`

### Usage

1. Run `npm start`
2. Checkout console output to see where local server is started. You can use all [links](#links) (except `preview`) by replacing https://mbaezpy.github.io/traduttore-api/ with url from the message: `Server started <url>`
3. Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
4. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
**TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
5. Once you finish with the changes you can run tests using: `npm test`
