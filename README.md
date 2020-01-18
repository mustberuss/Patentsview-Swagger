# Patentsview API Meets Swagger-UI

This repo was orginally generated using https://github.com/ReDoc-ly/create-openapi-repo#installation I've since switched it to a dependency free implementation using [swagger-ui-dist](https://www.npmjs.com/package/swagger-ui-dist) and two swagger objects.   I wrote a Swagger 2 json object by hand for the Patentview API since it lacked one.  I then used the online converter mentioned at https://github.com/LucyBot-Inc/api-spec-converter to generate an OpenAPI/Swagger 3 object.  

## Links
- Swagger-UI 
    + https://mustberuss.github.io/Patentsview-Swagger/ Swagger 2
    + https://mustberuss.github.io/Patentsview-Swagger/patentsviewswagger3.html OpenAPI/Swagger 3
- Patentsview API: https://www.patentsview.org/api/doc.html
- My observations on the API: http://patentsview.historicip.com/
- About Swagger-UI and this API in particular: http://patentsview.historicip.com/swagger/articles/

**Warning:** The API's ultra helpful X-Status-Reason header is not exposed to Swagger-UI. I've opened an issue with the API's provider.
