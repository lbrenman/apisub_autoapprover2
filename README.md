# API Builder API Subscription Auto Approver for Amplify Central

This API Builder project implements a webhook for Amplify Central API Subscriptions and auto approves the request. It is intended to be a Hello World Custom API Subscription Approval flow as described [here](https://blog.axway.com/dev-insights/hello-world-custom-api-subscription) but built using API Builder. I used API First methodology to build this API. The API was designed in Stoplight. Stoplight assets can be found [**here**](https://github.com/lbrenman/amplifycentralwebhookhandlerdefinition).

It requires a service account clientId and client Secret as described [here](https://blog.axway.com/apis/axway-amplify-platform-api-calls).

The project requires the following environment variables:
* **clientId** - from a service account as described above
* **clientSecret** - from a service account as described above
* **apicentralUrl** - https://apicentral.axway.com or the URL for your region
* **apikey** - an API Key that you provide. You pass this key as a header using apikey as the key and the value you enter here. These are configured in your Central Discovery Agent environment file
