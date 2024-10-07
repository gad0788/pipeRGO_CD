🌟 Excited to complete my latest DevOps project! 🌟

I’ve successfully deployed a test Java application leveraging a full cloud-native CI/CD pipeline with AWS, Terraform, Ansible, Jenkins, SonarQube, and ArgoCD. 

Project Highlights:

Infrastructure Setup: Used Terraform and Ansible to provision and configure AWS EC2 instances running Jenkins and SonarQube.
CI/CD Pipeline:
Jenkins triggers the pipeline, builds the Java app, and runs static code analysis with SonarQube.
After the build, the Docker image is pushed to Docker Hub.
The Kubernetes YAML file is automatically updated with the new image tag and committed to the Git repository.
ArgoCD detects the changes and automatically deploys the updated image to the Kubernetes cluster.
This end-to-end pipeline ensures continuous integration and continuous delivery with robust automation. 🎯