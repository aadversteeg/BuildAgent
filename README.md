# BuildAgent

Docker Image for Azure Devops Build Agent

Image is build and pushed using an Azure Devops Pipeline. 

To push the image make a service connection of type `Docker Registry` named `Azure Container Registry`. The image will be placed in repository `azure-devops-agent` with tag `latest` and `$(Build.BuildId)`.



## References

[Run a self-hosted agent in Docker](https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/docker?view=azure-devops)

