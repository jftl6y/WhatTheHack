# Challenge 02 - Writing API Policies in API Management - Coach's Guide

[<Previous Solution](./Solution-01.md) - **[Home](./README.md)** - [Next Solution>](./Solution-03.md)

## Introduction

The students will create API Policies which will affect the processing of requests and responses to APIs in API management.


## Description

- Students are suggested to implement the `ip-filter` and `rate-limit-by-key` policy
- For the `rate-limit-by-key` policy, the example for the counter-key value is typically the caller's IP address. However, when testing in the portal, this may not always be the same, so using a counter-key="1" will apply the rate limit to all calls to the policy, and is a good way to test.  
- For the `ip-filter` policy, the student will need to test from their own machine, getting their IP address and using it to test the filter.
    - The student will need to either 
        1. Turn off the Subscription Key required field in the API settings or 
        1. Use a tool such as Postman or other API testing tool to pass in the Ocp-Apim-Subscription-Key value (found in Subscription Keys) or 
        1. Use PowerShell as such

        ```powershell
        $headers = @{'Ocp-Apim-Subscription-Key' = 'aaaasubscriptionkeyhereaaa'}
        iwr https://apiminstance.azure-api-net -headers $headers
        ```

- Another good thing to point out is the APIM trace functionality, which give you detailed diagnostics of the entire request-backend-response-onerror cycle. To enable this, either
    1. Enable tracing in the APIM test console and click "Trace" instead of "Test" or
    1. Pass the Ocp-Apim-Trace header with value of true, e.g. `$headers += @{'Ocp-Apim-Trace'='true'}`

## Learning Resources

- [API Management policy reference](https://learn.microsoft.com/en-us/azure/api-management/api-management-policies)

[Back to Top](#challenge-02---writing-api-policies-in-api-management---coachs-guide)
