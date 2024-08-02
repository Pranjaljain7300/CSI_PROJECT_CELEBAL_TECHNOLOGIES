Implementing automated deployment pipelines in Azure DevOps to orchestrate Azure Kubernetes Service (AKS) deployments for scalable and resilient containerized applications.

Process:

1. Create a Resource Group
2. Create a Container registry 
3. Create a Kubernetes Cluster 
4. Create a new Pipeline 
 ->Create a new pipeline in Azure DevOps and select the forked repository as the source.
 ->Add a Docker task to build the image and push it to the container registry.
 ->Add a Kubernetes task to deploy the image to AKS.  
5. After build the pipeline , push it into the container registry and deploy into the AKS.
