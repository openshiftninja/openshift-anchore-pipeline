# Securing an OpenShift Container Image CI/CD Pipeline with Anchore

The files in this project are related to my writeup on integrating the Anchore container image scanning solution into an OpenShift/Jenkins CI/CD pipeline. I talked about setting up the OpenShift/Jenkins pipeline in this post:

https://blog.osninja.io/building-a-container-image-cicd-pipeline/

I'm following up on that post with this one:

https://blog.osninja.io/p/2c6a2686-a668-434b-8c8c-d45db94c2e48/

# Contents

This repo has three folders:

* **openshift** - this folder has the YAML defintions for the resources I create for the project in OpenShift. Mostly it is the default **NodeJS + MongoDB Persistent** template project, but these YAML files were the result of my configuration
* **jenkins** - this folder has the Jenkinsfile that represents the pipeline that I build
* **anchore** - this folder has the config.yaml and the docker-compose.yaml for the Anchore engine that I ran. 