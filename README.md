# Patentsview API Meets Swagger-UI

*2025-05-01 update*: The Patentsview API team has shutdown the original version of the API so my Swagger UI pages no longer work.  They have provided their own [Swagger UI page](https://search.patentsview.org/swagger-ui) for the new version of the API. **Important note:** An [API key](https://patentsview-support.atlassian.net/servicedesk/customer/portal/1/group/1/create/18) is now required


This repo was orginally generated using https://github.com/ReDoc-ly/create-openapi-repo#installation I've since switched it to a dependency free implementation using [swagger-ui-dist](https://www.npmjs.com/package/swagger-ui-dist) and two swagger objects.   I wrote a Swagger 2 json object by hand for the Patentview API since it lacked one.  I then used the online converter mentioned at https://github.com/LucyBot-Inc/api-spec-converter to generate an OpenAPI/Swagger 3 object.  

## Links
- Swagger-UI 
    + https://mustberuss.github.io/Patentsview-Swagger/ Swagger 2
    + https://mustberuss.github.io/Patentsview-Swagger/patentsviewswagger3.html OpenAPI/Swagger 3
- Patentsview API: https://patentsview.org/apis/purpose
- About Swagger-UI and this API in particular: https://patentsview.historicip.com/swagger/articles/
