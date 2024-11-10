# DevOps Course

## The goal

The course aims to offer in-depth knowledge of DevOps principles and essential AWS services necessary for efficient automation and infrastructure management. Participants will gain practical skills in setting up, deploying, and managing Kubernetes clusters on AWS, using tools like Kops and Terraform.

# Task 5: Simple Application Deployment with Helm

## File Structure
- **```.github/workflows/```**:
  The directory is where GitHub-specific files are stored, particularly workflows for GitHub Actions.
- **```README.md```**:  
  This file you're reading.
- **```wp-version```**:  
  We will need this file to deploy another version of WP.


## How to Use

1. **Clone the repository**
Clone the repository and navigate to the project directory:
```
git clone git@github.com:CiscoSA/rsschool-devops-course-tasks.git
cd rsschool-devops-course-tasks
git branch task_5
```
2. **Deploy another version of WP**  
   ```vi wp-version```
   Change the version of the image
   ```git commmit -am "Your commit"```
   ```git push```

## Steps

1. **Create Helm Chart**

   - Create a Helm chart for your application.

2. **Deploy the Application**

   - Deploy the WordPress application using the Helm chart.
   - Ensure the application is accessible from the internet.

3. **Store Artifacts in Git**

   - Store the WordPress application and Helm chart in a new git repository.

4. **Verify the Application**

   - Verify that the application is running and accessible.

5. **Additional Tasks**
   - Implement a CI/CD pipeline to automate the deployment of the WordPress.
   - Document the application setup and deployment process in a README file.

## Submission

- Provide a PR with the application and Helm chart in a new repository.
- Ensure that the application is accessible from the internet.
- Provide a PR with the CI/CD pipeline code for the application deployment.
- Provide a README file documenting the application setup and deployment process.