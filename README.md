# Dev Containers

A common pattern you will see across many HYPR projects is the use of containerised development environments. This serves a number of purposes:
- Creates a consistent environment across different developers' machines (regardless of OS)
- Makes the development environment more similar to cloud deployments
- You'll need much fewer tools installed and set up to get started (making switching between different projects easier too!)

For more detailed context, see [this Medium article](https://medium.com/swlh/building-a-dev-container-for-net-core-e43a2236504f) by Manfred Lange, one of our Principal Coding Architects.

## Requirements

#### For development containers
- Git client
- Docker Desktop (MacOS/Windows) or Docker Engine (Linux)

#### To develop directly inside a container
- VSCode
- VSCode Remote Development Extension 

This repo contains an example for a containerised Node.js API, but the concepts are applicable anywhere (the Medium article linked above sets up a .NET environment.)
