# Simple Backend Template

A minimal template for simple backend APIs used during the MVP phase and for experimentation.

## Requirements

* Minimal API pattern
    + Hello World endpoint: /api/hello
    + Health endpoint: /api/health
* Basic configuration
    + No secrets in code
* Simple health checks
* Console logging only
* Stateless
* CICD

## Risks

* Open to internet
* No authentication
* No storage
* No caching

## Stack

* Windows development environment
* VS Code IDE
* C# 8 on dotnet
* Powershell scripting
* Azure hosting
    + Azure App Service
* Azure DevOps Pipeline

## Excluded

Azure related stack excluded from this template:

* Functions
* VNET
* Private Endpoint
* API Management
* Key Vault
* App Config
* Blob storage
* SQL
* Cosmos DB
* Redis Cache
* Service Bus