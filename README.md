Deploy our web application in K8s cluster from private Docker registry (ECR).

Description:- Create Secret for credentials for the private Docker registry
              Configure the Docker registry secret in application Deployment component
              Deploy web application image from our private Docker registry
              

Pre-requisites:-  Create Docker Private Repo (ECR) on AWS           
------------------------------------------------------------------------------------------------------------------------------------

Steps to pull your images from Private Registry

a) Create a secret component that contains access tokens (credentials) for Docker Registry

b) Configure Deployment/Pod with imagePullSecrets


-----------------------------------------------------------------------------------------------------------------------------
Execution Order:- Please refer cli-commands.md file

Docker login comamnd will -create config.json file for secret
Use config.json content in secret file.

Check different ways of creating secret.




