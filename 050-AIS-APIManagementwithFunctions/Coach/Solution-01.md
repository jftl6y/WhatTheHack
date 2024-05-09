# Challenge 01 - Import and test APIs in API Management - Coach's Guide

[<Previous Solution](./Solution-00.md) - **[Home](./README.md)** - [Next Solution>](./Solution-02.md)

## Introduction

The students should be able to import APIs from an OpenAPI Spec as well as from an Azure Function.  This prepares them for the second challenge where they will be asked to write policies for these APIs.

## Description

Students will import APIs from the following two sources:

- [Scenario 01: Import an API using OpenAPI specification](#scenario-01-import-an-api-from-an-api-using-an-openapi-specification)
- [Scenario 02: Create an API application using Azure Functions](#scenario-02-create-an-api-application-using-azure-functions)

### Scenario 01: Import an API from an API using an OpenAPI specification

- Scenario 01: Students can import APIs from the public facing Catfacts API at <https://catfact.ninja>. This is a simple API that consists of the following operations:  
  1. GET /breeds Gets a list of breeds
  1. GET /fact Gets a random fact
  1. GET /facts Get a list of facts

Students should be able to import the API using the "Create from definition->OpenAPI" feature in API Management using the URL <https://catfact.ninja/docs/api-docs.json>

### Scenario 02: Create an API application using Azure Functions

- Scenario 02: Students create an Azure Function with an HttpTrigger. The Azure Function scaffolding will create a simple API that will reflect back the name parameter passed in to the function app `GET` or will reflect back the name parameter passed in to the function app in the request body `POST`

If the students want to author their function in the portal, **THEY MUST** choose the .NET framework with version 6 (LTS), in-process model. If they choose any other framework they will need to develop the function locally and deploy to the function app.

Students should be able to import the API using the "Create from Azure resource->Function App" feature in API Management.

After both API types are imported, they should be able to test their APIs in the API management management portal using the test feature.

[Back to Top](#challenge-01---import-and-test-apis-in-api-management---coachs-guide)
