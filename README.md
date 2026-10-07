# AWS Full-Stack Application Deployment with CloudFront

## Project Overview

This project demonstrates the deployment of a full-stack application on AWS using Docker, Amazon S3, and Amazon CloudFront.

The application was containerized using Docker, deployed and tested, with the frontend hosted on Amazon S3 and delivered through Amazon CloudFront.

## Architecture

```text
User
  |
  v
CloudFront
  |
  v
Amazon S3
  |
  v
Frontend
  |
  v
Backend API
  |
  v
Database
```

## Technologies Used

* Git & GitHub
* Docker
* Docker Compose
* Docker Buildx
* AWS CLI
* Amazon S3
* Amazon CloudFront
* Frontend Application
* Backend API
* Database

## Deployment Steps

1. Installed and configured Git and Docker.
2. Cloned the application repository.
3. Modified the Docker Compose configuration.
4. Built and started the application containers.
5. Verified the backend API using `curl`.
6. Prepared the frontend application.
7. Verified AWS CLI access using `aws sts get-caller-identity`.
8. Uploaded the frontend files to Amazon S3.
9. Created an Amazon CloudFront distribution.
10. Configured the CloudFront origin and cache behavior.
11. Updated the frontend configuration with the required URL.
12. Created a CloudFront cache invalidation.
13. Verified the application through the CloudFront URL.
14. Tested employee add, update, and delete operations.
15. Committed and pushed the changes to GitHub.

## Verification

The following were verified successfully:

* Backend API response
* Frontend accessibility
* S3 frontend files
* CloudFront distribution
* CloudFront URL
* Employee creation
* Employee update
* Employee deletion

## Repository

GitHub Repository:

`https://github.com/subashree21/aws-full-stack-cloudfront`

## CloudFront URL

`https://d1jwve5ou9jz30.cloudfront.net/`

## Conclusion

The full-stack application was successfully deployed and configured with Amazon CloudFront. The application was verified through the CloudFront URL and the major application functionalities were tested successfully.
