---
page_type: sample
languages:
- azdeveloper
- nodejs
- bicep
- typescript
- html
products:
- azure
- azure-cosmos-db
- azure-app-service
- azure-monitor
- azure-pipelines
urlFragment: todo-nodejs-mongo
name: React Web App with Node.js API and MongoDB on Azure
description: A complete ToDo app on Azure App Service with Node.js API and Azure Cosmos API for MongoDB for storage.
---
<!-- YAML front-matter schema: https://review.learn.microsoft.com/en-us/help/contribute/samples/process/onboarding?branch=main#supported-metadata-fields-for-readmemd -->

# React Web App with Node.js API and MongoDB on Azure

!["Screenshot of deployed ToDo app"](assets/web.png)

<sup>Screenshot of the deployed ToDo app</sup>

### Prerequisites

The following prerequisites are required to use this application. Please ensure that you have them all installed locally.

- [Azure Developer CLI](https://aka.ms/azd-install)
- [Node.js with npm (18.17.1+)](https://nodejs.org/) - for API backend and Web frontend

### Application Architecture

This application utilizes the following Azure resources:

- [**Azure App Services**](https://docs.microsoft.com/azure/app-service/) to host the Web frontend and API backend
- [**Azure Cosmos DB API for MongoDB**](https://docs.microsoft.com/azure/cosmos-db/mongodb/mongodb-introduction) for storage
- [**Azure Monitor**](https://docs.microsoft.com/azure/azure-monitor/) for monitoring and logging
- [**Azure Key Vault**](https://docs.microsoft.com/azure/key-vault/) for securing secrets

Here's a high level architecture diagram that illustrates these components. Notice that these are all contained within a single [resource group](https://docs.microsoft.com/azure/azure-resource-manager/management/manage-resource-groups-portal), that will be created for you when you create the resources.

!["Application architecture diagram"](assets/resources.png)

# Deployment using Terraform

In this repository you can find the Terraform to deploy the infrastructure and azure CI/CD pipeline to automate the deployment for the React Web App with Node.js API and MongoDB on Azure

# React Web App with Node.js API and MongoDB on Azure

Below repository includes a complete ToDo app on Azure App Service with Node.js API and Azure Cosmos API for MongoDB for storage, made for demonstration purposes only.

[Simple-Flask-Server-Appservice](https://github.com/Azure-Samples/simple-flask-server-appservice.git)