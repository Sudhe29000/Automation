# Automation
Team site for automation and deployment of docker images and basic smple of scripting the multi cloud resource management
There are basic transfrom template added to create docker image and this need fine tuning to deploy any specific image 
( Custom iage need to be in docker registry to get that published ) - all code is in beta 
providers.tf - This file containt the basic template for provider
main.tf - Sample file that contain the docker contianer configuration 
More info: 
terranine is an integaration tool that support secure data integration between cloud VM's
https://learn.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-terraform
https://github.com/hashicorp/terraform/blob/main/docs/architecture.md
https://developer.hashicorp.com/terraform/tutorials/docker-get-started/docker-build
Notes:
If you are using nodejs then install touch using following command 
npm install touch-cli -g
