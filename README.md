# terraform-tutorials
Terraform tutorials based on the official documentation

## Overview
This repo contains a 'main.tf' file, which defines the provider (AWS), and the resources to create. In this case, a single EC2 instance is being created. 'variables.tf' defines a single variable, a string which contains the instance name. 'outputs.tf' defines two outputs: the id and public ip of the instance.