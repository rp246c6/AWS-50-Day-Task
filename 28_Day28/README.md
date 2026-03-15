Creating a Private ECR Repository
--
why to create a private ECR repository.
--
Creating a private repository in AWS (e.g., using Amazon ECR for containers or AWS CodeCommit for source code) is
primarily for security, access control, and seamless integration within your private cloud environment and CI/CD pipelines.

checklist for implementation:
1)Verify Docker & AWS CLI on aws client.
2)Create the ECR Repository.
3)Authenticate Docker to ECR.
4)Build the Docker Image.
5)Tag the Image for ECR.
6)Push the Image to ECR.
7)Verify Image in ECR.
