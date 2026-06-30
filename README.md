# Azure Functions - Java HTTP Trigger

A simple serverless application built using **Java** and **Azure Functions**. This project demonstrates creating, running, and deploying an HTTP-triggered Azure Function.

## Technologies Used

- Java
- Azure Functions
- Maven
- Azure Functions Core Tools
- Visual Studio Code

## Features

- HTTP Trigger Function
- Supports GET and POST requests
- Runs locally using Azure Functions Core Tools
- Deployable to Azure Function App

## Running Locally

```bash
mvn clean package
mvn azure-functions:run
```

The function will be available at:

```
http://localhost:7071/api/HttpExample
```

Example:

```
http://localhost:7071/api/HttpExample?name=Arun
```

## Project Structure

```
src/
host.json
pom.xml
local.settings.json (ignored)
```

## Learning Outcome

This project demonstrates:

- Azure Functions
- Serverless Computing
- Local Function Development
- HTTP Triggers
- Deployment to Azure
