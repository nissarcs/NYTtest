"# NYTtest" THis project uses Retrofit to retrieve data from API.It makes it relatively easy to retrieve and upload JSON (or other structured data) via a REST based webservice.Retrofit uses the OkHttp library for HTTP requests.

To work with Retrofit you basically need the following three classes:
Model class which is used as a JSON model
Interfaces that define the possible HTTP operations
Retrofit.Builder class - Instance which uses the interface and the Builder API to allow defining the URL end point for the HTTP operations.

Every method of an interface represents one possible API call. It must have a HTTP annotation (GET, POST, etc.) to specify the request type and the relative URL. The return value wraps the response in a Call object with the type of the expected result.
