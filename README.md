# Service Intianlization
**Prerequists**
1) Add azure credentials to AzureDevops Library with this name "github"
  variables are: 
   *  ORGANIZATION_NAME
   * GIT_EMAIL
   * GIT_USER_NAME
   * AZURE_ACCESS_KEY
# How Pipeline Work
  1) when you trigger the pipeline it will ask you for service name 
  2) After type service name it will check if this serice already exist or not
  3) It will intialize the java application with archetype in this demo i use (maven-archetype-archetype)
  4) It will create a repository on Azure Devops repo for this service 
  5) it will create separete  Pipeline for this service on Azure-Pipeline