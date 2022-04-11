# Helpers

Various helper classes for usage in Azure Functions and more.

## AzureFunction-trigger-LogicApp.csx

Translates query parameters to call an Azure Logic App.  

This small Azure function code reads a query parameter from the URL and translates it into a JSON body message. 
Another endpoint is called from the function app. Here it´s an Azure Logic App that reads the body message and processes the passed in data. 
The function then returns an OK status (HTTP 200). This example is intended as a suggestion to be further adapted.

