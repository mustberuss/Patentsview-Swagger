# Patentsview OpenAPI Specification

## Links
- API: https://www.patentsview.org/api/doc.html

- SwaggerUI: https://mustberuss.github.io/Patentsview-Swagger/swagger-ui/
- Look full spec:
    + JSON https://mustberuss.github.io/Patentsview-Swagger/patentsview.json
    + YAML https://mustberuss.github.io/Patentsview-Swagger/patentsview.yaml
- My observations on the api: http://patentsview.historicip.com/

**Warning:** The ultra helpful X-Status-Reason header is not exposed to Swagger-UI. I've opened an issue with the api provider.

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and `cd`
    + Run `npm install`

### Usage

1. Run `npm start`
2. Checkout console output to see where local server is started. You can use all [links](#links) (except `preview`) by replacing https://mustberuss.github.io/Patentsview-API/ with url from the message: `Server started <url>`
3. Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
4. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
**TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
5. Once you finish with the changes you can run tests using: `npm test`
6. Share you changes with the rest of the world by pushing to GitHub :smile:

This repo was generated using https://github.com/ReDoc-ly/create-openapi-repo#installation
