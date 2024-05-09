# Challenge 01 - Import and test APIs in API Management

[<Previous Challenge](./Challenge-00.md) - **[Home](../README.md)** - [Next Challenge>](./Challenge-02.md)

## Pre-requisites

- You should have completed Challenge 00

## Introduction

You are a cloud engineer for Runva - a global health and wellness company that provides solutions for individuals who takes running as sport, providing them a platform to track running activities, analyze performance and recommend plans to help them train smarter and safer.  They are going to embark on a six-month project to modernize their integration solution hosted on-premises and migrate them to Azure integration services.  Since this is their first foray in Azure, you are tasked to create a proof-of-concept (POC) that captures several integration patterns.


## Description

As a cloud engineer, you would like to be able to utilize Azure API Management to manage and secure the APIs in your organization. To assess the capabilities of Azure API Management, you'll start by importing APIs into API Management.

There are two scenarios you would like to prove:

### Scenario 01: Import an API from an API using an OpenAPI specification (aka Swagger)

- The Cat Facts API is a public API which presents random information about cats. It is available at <https://catfact.ninja>
- The Cat Facts API uses the OpenAPI Specification (aka Swagger) to describe the operations available on the API
- For this challenge, locate the OpenAPI specification and import the specification into API Management
- Demonstrate you are able to test each operation in the API Management API console

### Scenario 02a: Create an API application using Azure Functions

- Create an Azure Function with an HttpTrigger. The default scaffolding code is sufficient for the purposes of this hack, though feel free to play with the code.
  - **_NOTE_** If you are developing your function in the portal, make sure to select the .NET runtime with the 6 (LTS) in-process model.
- Test your Function App in the Function App test console

### Scenario 02b: Import the Azure Function as an API in API Management

- In API Management, import the Azure Function you create into API Management
- Test the GET and POST operations against your Azure Function in the API Management test console

## Learning Resources

- [Azure API Management](https://docs.microsoft.com/en-us/azure/api-management/api-management-key-concepts)
  - [Azure API Management - Import an OpenAPI specification](https://learn.microsoft.com/en-us/azure/api-management/import-api-from-oas?tabs=portal)
  - [Import an Azure Function App as an API in Azure API Management](https://docs.microsoft.com/en-us/azure/api-management/import-function-app-as-api)
- [Azure Functions - Create your first function in the Azure portal](https://learn.microsoft.com/en-us/azure/azure-functions/functions-create-function-app-portal?pivots=programming-language-csharp)

## Advanced Challenges

- Test your imported APIs outside of API Management using a tool such as Postman or PowerShell.
- Find a different API and import it from [Public APIs](https://github.com/public-apis/public-apis)

[Back to Top](#challenge-01---import-and-test-apis-in-api-management)
