# AWS-CI-CD-Project
This project is all about crafting a seamless CI/CD pipeline to efficiently build and deploy a Flask Python application onto an AWS EC2 instance using AWS managed CI-CD services.


Here's a brief overview of the project and the technologies involved:

🔹 GitHub: Served as the source code management (SCM) and version control system (VCS), hosting our Flask application's codebase.

🔹 AWS CodeBuild: Integrated with GitHub to automatically trigger builds upon code changes, ensuring continuous integration with every commit.

🔹 AWS CodePipeline: Acted as the orchestrator, seamlessly connecting our CI and CD processes. It was fascinating to see how CodePipeline streamlined the workflow from code update to deployment.

🔹 AWS CodeDeploy: Took care of the continuous deployment part, automating the application deployment to AWS EC2 instances. It ensured our Flask app was always up-to-date with the latest changes.

🔹 AWS EC2: Hosted our Flask application, providing a scalable and reliable environment for deployment.

🔹 AWS IAM: Was crucial in setting up the necessary permissions, allowing our services to interact securely and efficiently.

🔹 AWS S3: Used to store the resource kit file related to CodeDeploy, facilitating smooth deployments.

🔹 Docker: Played a key role in containerizing our Flask application, ensuring consistency across different development and production environments.

🔹 AWS Systems Manager (Parameter Store): for storing the docker credentials to be used in build spec file.

This project was not just about using these tools but understanding how they integrate and complement each other to create a robust, scalable, and efficient CI/CD pipeline.
