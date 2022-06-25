# Deploy-a-high-availability-web-app-using-CloudFormation
Deploy Infrastructre as Code (IAC) | Udacity Advanced Cloud DevOps Nanodegree Program


## About The Project

This is the second assessment project for Udacity's Deploy Infrastructure as Code (IAC) course which is the second part of Udacity Advanced Cloud DevOps Nanodegree Program.
This project only includes the requirments for the project to be accepted.

## Installation

To get started:

* create aws stack to create the network infrastructe by executing this command in your bash terminal from VS Code `./create.sh udacityProj2-network ./network.yml network-parameters.json`
* create aws stack to create the servers infrastructe by executing this command in your bash terminal from VS Code `./create.sh udacityProj2-servers ./servers.yml server-parameters.json`

## Description
In the project, I deployed web servers for a highly available web app using CloudFormation. I wrote the code that creates and deploys the infrastructure and application.
The Cloud architecture diagram can be found in the project files with the file name "CloudArchitectureImage.jpeg" as the following:
![alt text](https://github.com/Mohamed-Alieldin/Deploy-a-high-availability-web-app-using-CloudFormation/blob/main/CloudArchitectureImage.jpeg)
