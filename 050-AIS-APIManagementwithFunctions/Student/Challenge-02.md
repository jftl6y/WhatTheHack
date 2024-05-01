# Challenge 02 - Writing API Policies in API Management


[<Previous Challenge](./Challenge-01.md) - **[Home](../README.md)** - [Next Challenge>](./Challenge-03.md)

## Pre-requisites

- You should have completed Challenge 01

## Introduction
Now that you've imported some APIs into your API Management instance, apply some API policies. 

## Description
- Choose one of the APIs you imported in Challenge 01. Apply an `ip-filter` policy and a `rate-limit-by-key` policy to the incoming request.

## Success Criteria
- Verify that you are able to rate limit your policy. If a rate limit policy hits its limit, it will return a `429 Too Many Requests` error instead of the normal `200 OK` or `202 Accepted` response.

## Learning Resources
- [Policies in Azure API Management](https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-policies)
- [API Management policy reference](https://learn.microsoft.com/en-us/azure/api-management/api-management-policies)
- [API Management Set Body Policy](https://learn.microsoft.com/en-us/azure/api-management/set-body-policy)


## Advanced Challenges
- Modify the Response Body using API Management Policies using the `set-body` policy. Change the name being returned by the Azure Function app. 

[Back to Top](#challenge-02---writing-api-policies-in-api-management)
