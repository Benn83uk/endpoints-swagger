# Google Cloud Endpoints & Java
This sample demonstrates how to use Google Cloud Endpoints using a Java backend.

For a complete walkthrough showing how to run this sample in different environments, see the [Google Cloud Endpoints Quickstarts](https://cloud.google.com/endpoints/docs/quickstarts).

##LINKS BEN USED -
Initial Endpoints project: https://cloud.google.com/endpoints/docs/openapi/get-started-app-engine
Adding Swagger: https://cloud.google.com/endpoints/docs/openapi/adding-swagger 
x-google-allow: https://cloud.google.com/endpoints/docs/openapi/openapi-extensions

##Deployment
From project home directory
- Endpoints: gcloud endpoints services deploy openapi-appengine.yaml
Then replace the service config id in app.yaml (from the output of endpoitns deployment)
- config_id: "<NEW CONFIG ID>"
Then deploy to app engine
- mvn appengine:deploy