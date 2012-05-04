Welcome to the OpenLeague project.
=============================

OpenLeague is a Sports fixture management system.

## Prerequisites

* [Windows Azure PowerShell Cmdlets](http://wappowershell.codeplex.com/)
* [Running PowerShell under .Net 4](http://stackoverflow.com/questions/2094694/how-can-i-run-powershell-with-the-net-4-runtime)

## Setting up the environment for Windows Azure

> .\build.ps1 env

Type in your subscription id and then import the certificate that the build creates into your Windows Azure management certificate list.
The build script also creates the tools\environment.xml that contains all the environment variables needed for Azure deployment.

## Building the solution

> .\build.ps1

## Deploying to Azure

> .\build.ps1 deploy

