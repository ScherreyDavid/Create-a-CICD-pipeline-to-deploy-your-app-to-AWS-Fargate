
# Created a CICD Pipeline to Deploy app to AWS Fargate

I created a CI/CD pipeline to deploy my app to AWS Fargate using CodeCommit, CodeBuild, and CodeDeploy. I configured CodeCommit as a source control repository and created a CodeDeploy application and deployment group. I built a CI/CD pipeline that performed a blue/green deployment
## Tasks

Task 1: Explore the application and review the Fargate configuration

Task 2: Configure CodeCommit as a source control repository

Task 3: Create a CodeDeploy application and deployment group

Task 4: Build your CI/CD pipeline

Task 5: Observe a blue/green deployment

## Tech Stack
**Client:** Javascript, JSON, Dockerfile, YAML

**AWS Cloud Services:** AWS Cloud9,
AWS CodeBuild,
AWS CodeCommit,
AWS CodeDeploy,
AWS CodePipeline,
Amazon Elastic Container Registry (Amazon ECR) and
Amazon ECS, 
Fargate, IAM


## Screenshots

[![Green1.png](https://i.postimg.cc/m2YGMK0s/Green1.png)](https://postimg.cc/VdkTPZfG)

#Title: Automating AWS ECS Deployments with CI/CD Pipeline

In today's fast-paced world of software development, automating deployments is crucial for maintaining efficiency and consistency in your application's delivery process. Amazon Elastic Container Service (ECS) combined with Continuous Integration and Continuous Deployment (CI/CD) pipelines provides a powerful solution for automating deployments in the AWS cloud. In this blog post, we will walk through a project that demonstrates how to set up a CI/CD pipeline to automate ECS deployments.

Project Overview
The project involves deploying a web application using ECS. We will use a CI/CD pipeline to automate the deployment process, enabling us to quickly and reliably deliver updates to our application. Here are the key tasks we'll cover:

Setting Up AWS Cloud9 Environment

We'll begin by setting up an AWS Cloud9 environment, which is a cloud-based Integrated Development Environment (IDE) provided by AWS. This environment will be used for writing, running, and debugging code within your browser.
Configuring AWS CodeCommit as a Source Control Repository

We'll connect our Cloud9 environment to AWS CodeCommit, a fully managed source control service, to store our application's source code. We'll create essential configuration files and edit the source code.
Creating a CodeDeploy Application and Deployment Group

We'll set up a CodeDeploy application and deployment group, which are essential for orchestrating deployments. These configurations define how updates will be deployed to our ECS service.
Building a CI/CD Pipeline

The heart of our project is the creation of a CI/CD pipeline using AWS CodePipeline. This pipeline will automatically build and deploy our application whenever changes are pushed to CodeCommit.
Observing a Blue/Green Deployment

Finally, we will observe our pipeline in action as it performs a blue/green deployment of our application. We'll monitor each stage of the pipeline and verify the successful deployment of our updated application.

Task 1: Setting Up AWS Cloud9 Environment
To start, we create an AWS Cloud9 environment and ensure it's configured correctly.

Task 2: Configuring AWS CodeCommit as a Source Control Repository
In this task, we set up CodeCommit as our source control repository. We create essential configuration files like buildspec.yaml, appspec.yaml, and taskdef.json to define our deployment process.

Task 3: Creating a CodeDeploy Application and Deployment Group
We prepare for our blue/green deployment by creating a CodeDeploy application and deployment group. These configurations help manage the deployment of our ECS service.

Task 4: Building a CI/CD Pipeline
The core of our project is setting up a CI/CD pipeline using AWS CodePipeline. This pipeline automates the entire build and deployment process whenever code changes are detected in CodeCommit.

Task 5: Observing a Blue/Green Deployment
Finally, we observe our pipeline in action as it performs a blue/green deployment. We monitor each stage of the pipeline and verify the successful deployment of our updated application.

Conclusion
In this project, we've automated the deployment of an AWS ECS application using a CI/CD pipeline. This approach streamlines the deployment process, enhances reliability, and ensures consistency in delivering updates to our application. By setting up the pipeline, we can easily scale our deployment process as our application evolves.

AWS provides a robust set of tools and services for automating and managing deployments, and this project serves as a practical example of how to leverage those tools effectively.

CI/CD pipelines are essential for modern software development, allowing teams to deliver changes quickly and reliably while maintaining a high level of confidence in the deployment process. If you're working with AWS ECS or similar services, setting up a CI/CD pipeline should be a key part of your development workflow.

This project provides a foundation for further exploration and customization of CI/CD pipelines on AWS. As you continue to develop and improve your applications, these automated deployment processes will be invaluable for ensuring smooth and efficient updates.


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://katherineoelsner.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/david-scherrey-iii/)


