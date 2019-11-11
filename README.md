[![Docker Build Status](https://img.shields.io/docker/cloud/build/joachimveulemans/azure-host-agent)](https://hub.docker.com/r/joachimveulemans/azure-host-agent/builds)
[![Docker Automated Status](https://img.shields.io/docker/cloud/automated/joachimveulemans/azure-host-agent)](https://hub.docker.com/r/joachimveulemans/azure-host-agent)

# Azure Host Agent

This repo contains an Azure Host Agent for Azure Pipelines.

## Running the container

`sudo docker run -d -e AZP_URL= -e AZP_TOKEN= -v /var/run/docker.sock:/var/run/docker.sock joachimveulemans/azure-host-agent:latest`
