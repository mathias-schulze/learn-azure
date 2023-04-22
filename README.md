# Learn Azure

## Setup

Install CLI ([Download](https://learn.microsoft.com/de-de/cli/azure/install-azure-cli-windows?tabs=azure-cli)) and Core Tools ([Download](https://learn.microsoft.com/de-de/azure/azure-functions/functions-run-local?tabs=v4%2Cwindows%2Ccsharp%2Cportal%2Cbash#v4)), verify installation and login (opens browser).

    az --version
    az login

## Functions

Run the following commands to create the function and run it locally.

    ./gradlew jar
    ./gradlew azureFunctionsRun

Deploy with:

    ./gradlew azureFunctionsDeploy