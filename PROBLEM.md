## Problem Statement: Experiment with deploying Spring Boot application on K8s cluster in AKS

* In this Exercise, you will deploy a Spring Boot application on K8s Cluster in AKS.
   
This exercise contains following folders 
    
    - k8s              - contains manifest files, these files are explained below
    - service-app      - This is a Spring Boot application
    
This exercise contains following files in k8s folder
    
    - springboot.yml   - This is to create the deployment, service of type LoadBalancer for service-app

**Note**: You need to go through the comments thoroughly and complete the exercise.
    
Understand and do the following steps to complete this exercise:
    
    1. Verify that AKS cluster is created and is ready.
    2. Push the service-app docker image to Docker Hub.
    3. Implement `springboot.yml` file to define the deployment, service of type LoadBalancer for service-app.
    4. Test the service-app
        - Test the url `<external-ip>/api/v1/hello`.
 
        
  