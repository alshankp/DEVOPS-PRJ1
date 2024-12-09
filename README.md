# DEVOPS-PRJ1
DevOps Lifecycle Implementation for Abode Software
In this project, I implemented the complete DevOps lifecycle for Abode Software, a company that wanted to automate its software delivery process. The goal was to streamline development, testing, and deployment, ensuring faster and more reliable releases.

What I Did:

CI/CD Pipeline Setup: I created a Continuous Integration/Continuous Deployment (CI/CD) pipeline using Jenkins, Docker, and Ansible. This pipeline automated the process of building, testing, and deploying code whenever a new change was made.

Build: Every time code was pushed to the repository, the pipeline automatically triggered a build process.
Test: The pipeline ran automated tests to ensure that new changes didn't break the application.
Deployment: After passing the tests, the application was automatically deployed to the production environment.
Dockerization: I containerized the application using Docker. This meant that the application and all its dependencies were packaged into a container, making it easier to deploy and run consistently across different environments.

Automation with Ansible: I used Ansible for automating infrastructure management. This included setting up servers, installing necessary software, and configuring the environment to ensure everything worked seamlessly.

Git Workflow Integration: I set up a Git workflow to ensure proper version control. I made sure that when code changes were pushed to the master branch, the application was tested and deployed to production. If changes were pushed to the develop branch, they would only be tested but not deployed immediately.

Technologies Used:

Jenkins: For automating the CI/CD pipeline.
Docker: To containerize the application for easy deployment.
Ansible: For automating the configuration of infrastructure.
Git: For version control and managing the source code repository.
This project helped Abode Software improve its development process by automating manual tasks, reducing deployment time, and ensuring consistent delivery of high-quality software.
