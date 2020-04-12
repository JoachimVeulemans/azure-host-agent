[![Azure DevOps builds](https://img.shields.io/azure-devops/build/joachimveulemans/1b53e530-587a-41e2-beae-d88bc385bc1d/32?label=CI%20Build)](https://dev.azure.com/JoachimVeulemans/azure-host-agent/_build?definitionId=32)
[![Azure DevOps builds](https://img.shields.io/azure-devops/build/joachimveulemans/1b53e530-587a-41e2-beae-d88bc385bc1d/33?label=CD%20Build)](https://dev.azure.com/JoachimVeulemans/azure-host-agent/_build?definitionId=33)

# Azure Host Agent

This repo contains an Azure Host Agent for Azure Pipelines.

## Running the container

`sudo docker run -d -e AZP_URL= -e AZP_TOKEN= --name azure-host-agent -v /var/run/docker.sock:/var/run/docker.sock registry.joachimveulemans.be/azure-host-agent:latest`
