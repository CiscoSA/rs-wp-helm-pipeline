## Submission

- Provide a PR with the application and Helm chart in a new repository.
- Ensure that the application is accessible from the internet.
- Provide a PR with the CI/CD pipeline code for the application deployment.
- Provide a README file documenting the application setup and deployment process.

## Evaluation Criteria (100 points for covering all criteria)

1. **Helm Chart Creation (40 points)**

   - A Helm chart for the WordPress application is created.
     
     - https://github.com/CiscoSA/rs-wp-helm/tree/main/Chart-wp

     ![](Screenshots/task5_1.png)


2. **Application Deployment (30 points)**

   - The application is deployed using the Helm chart.
     
     https://github.com/CiscoSA/rs-wp-helm/actions/runs/11767863023/job/32777021131#step:4:10

     ![](Screenshots/task5_2.png)

     https://github.com/CiscoSA/rs-wp-helm/actions/runs/11767863023/job/32777021131#step:5:27

     ![](Screenshots/task5_3.png)

   - The application is accessible from the internet.

     ![](Screenshots/task5_4.png)

     ![](Screenshots/task5_5.png)     

3. **Repository Submission (5 points)**

   - A new repository is created with the WordPress and Helm chart.

     - https://github.com/CiscoSA/rs-wp-helm/tree/main/Chart-wp

     ![](Screenshots/task5_1.png)


4. **Verification (5 points)**

   - The application is verified to be running and accessible.

     ![](Screenshots/task5_3.png)

     ![](Screenshots/task5_4.png)

     ![](Screenshots/task5_5.png)     


5. **Additional Tasks (20 points)**
   - **CI/CD Pipeline (10 points)**
     - A CI/CD pipeline is set up to automate the deployment of the application.

       https://github.com/CiscoSA/rs-wp-helm-pipeline/blob/task_5/.github/workflows/deploy.yml

       https://github.com/CiscoSA/rs-wp-helm-pipeline/actions/runs/11767992698/job/32777306447#step:5:28

       ![](Screenshots/task5_5.png)     
       

   - **Documentation (10 points)**
     - The application setup and deployment process are documented in a README file.

       https://github.com/CiscoSA/rs-wp-helm-pipeline/blob/task_5/README.md

       https://github.com/CiscoSA/rs-wp-helm/blob/main/README.md
