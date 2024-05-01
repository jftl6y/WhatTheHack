# What The Hack - AIS - API Management - Coach Guide

## Introduction

Welcome to the coach's guide for the Azure Integration Services - API Management Hack. Here you will find links to specific guidance for coaches for each of the challenges.

**NOTE:** If you are a Hackathon participant, this is the answer guide. Don't cheat yourself by looking at these during the hack! Go learn something. :)

## Coach's Guides
-  Challenge 0: **[Prepare your Development Environment](Solution-00.md)**
   - Get yourself ready to build your integration solution
-  Challenge 1: **[Import and test APIs in API Management](Solution-01.md)**
   - Import APIs to API Management.
-  Challenge 2: **[Writing API Policies in API Management](Solution-02.md)**
   - Write APIs to protect and manipulate the request/response.
-  Challenge 3: **[Create API Product](Solution-03.md)**
   - Package APIs into Products
-  Challenge 4: **[Customizing and publishing the Developer Portal](Solution-04.md)**
   - Customize the Developer Portal and demonstrate how developers can use it to discover, test and manage their subscription to APIs.
-  Challenge 5: **[Integration with Entra ID](Solution-05.md)**
    - Add Entra ID integration for user authentication

## Coach Prerequisites 

This hack has pre-reqs that a coach is responsible for understanding and/or setting up BEFORE hosting an event. Please review the [What The Hack Hosting Guide](https://aka.ms/wthhost) for information on how to host a hack event.

The guide covers the common preparation steps a coach needs to do before any What The Hack event, including how to properly configure Microsoft Teams.

### Student Resources

Before the hack, it is the Coach's responsibility to download and package up the contents of the `/Student/Resources` folder of this hack into a `Resources.zip` file. The coach should then provide a copy of the Resources.zip file to all students at the start of the hack.

Always refer students to the [What The Hack website](https://aka.ms/wth) for the student guide: [https://aka.ms/wth](https://aka.ms/wth)

**NOTE:** Students should **not** be given a link to the What The Hack repo before or during a hack. The student guide does **NOT** have any links to the Coach's guide or the What The Hack repo on GitHub.  

### Additional Coach Prerequisites 
- Visual Studio Code 1.63 or higher 
- Azure CLI 2.20.0 or higher
- Azure DevOps project or GitHub project

## Azure Requirements

These Azure requirements should be shared with a stakeholder in the organization that will be providing the Azure subscription(s) that will be used by the students.

This hack requires students to use an account that have Owner access to an Azure subscription so they can create and consume Azure resources such as: 

- API Management Service
- Azure Function Apps

Moreover, check that the account the students will use have the right permissions to be able to create new AAD application registrations (service principals).  If the student accounts do not have this permission, then ask if your AAD Global Administrator can allow it, or create app-registrations (service principals) on the student's behalf for the hack.  Steps on how do this can be found [here](https://docs.microsoft.com/en-us/azure/active-directory/develop/howto-create-service-principal-portal#permissions-required-for-registering-an-app).


## Suggested (abbreviated) Hack Agenda 

- Challenge 0 (30 minutes)
- Challenge 1 (30 minutes)
- Challenge 2 (1 hour)
- Challenge 3 (30 minutes)
- Challenge 4 (1 hour)
- Challenge 5 (30 minutes)

## Repository Contents

- `./Coach`
  - Coach's Guide and related files
- `./Coach/Solutions`
  - Solution files with completed example answers to a challenge
- `./Student`
  - Student's Challenge Guide
- `./Student/Resources`
  - Resource files, sample code, scripts, etc meant to be provided to students. (Must be packaged up by the coach and provided to students at start of event)





