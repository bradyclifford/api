# Overview

## Best Practices
* https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design
* https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md
* http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api
* http://www.restapitutorial.com/lessons/restquicktips.html

### Request, Status & Error Codes
* https://docs.telerik.com/platform/backend-services/javascript/apireference/RESTfulAPI/error_codes
* https://developer.springcm.com/guides/rest-api-response-and-error-codes
* https://cloud.google.com/storage/docs/json_api/v1/status-codes
* https://docs.microsoft.com/en-us/rest/api/storageservices/common-rest-api-error-codes

#### Validation
https://www.bennadel.com/blog/2434-http-status-codes-for-invalid-data-400-vs-422.htm

#### Error Handling
* https://www.devtrends.co.uk/blog/handling-errors-in-asp.net-core-web-api
* https://stackoverflow.com/questions/38630076/asp-net-core-web-api-exception-handling

##### Error Response Structure
http://blog.restcase.com/rest-api-error-codes-101/

## Hypertext Application Language
Lean Approach: http://stateless.co/hal_specification.html
Should use header: https://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html#sec14.30

## Versioning
Suggested by many to use Uri with a version for major releases.  Use header versioning for minor version.
