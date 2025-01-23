# nodejs-app
This repo is for github actions

Steps:

 1. Write the GitHub Actions Workflow in the following directory path

    `$ .github/workflows/ci-cd.yaml`

 2. Create the Dockerfile for the NodeJs application

    ` $ app/Dockerfile `

 3. Create a deployment manifest file

    ` $ k8s/deployment.yaml`

 4. Create a service manifest file

   ` $ k8s/service.yaml`

 5. Add the following secrets in GitHub repository 
   
    ` DOCKER_USERNAME `

    ` DOCKER_PASSWORD `

    ` KUBECONFIG `

 6. Run the Pipeline: Github will automatically run the pipeline after commit.
