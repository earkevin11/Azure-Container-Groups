# Azure-Container-Groups

# What is a Container Group?
- Container group is a collection of containers that gets scheduled on the same host machine and share the same resources, network, and storage volumes.
- Deployment of the container group can be done via ARM temploate or a YAML file

# What is the purpose of Container groups?
- Purpose is to host multiple applications within the same host machine. Each application will be on a unique container


# Kubernetes
- Used for managing containers at scale
- Azure Kubernetes is a managed service for Kubernetes on Azure
- Users can deploy containers on the Kubernetes cluster by pulling the images from the container registry
