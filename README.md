In this round you need to solve the two challenges mentioned as below.

### I. Write Terraform code for the following tasks:
---------------------------------------------------
1. Cross Account S3-SNS-SQS Integration
Create resources:
In Account A :
a. Create S3 Bucket `Test-Source-Bucket`
b. Create SNS Topic - `Test-SNS`
In Account B
a. Create SQS - Test-SQS

Requirement: Whenever any new file is uploaded to the S3 Bucket Test-Source-Bucket, the bucket should send a notification to SNS Test-SNS.
Subscribe the SQS queue Test-SQS to the SNS topic Test-SNS, such that when a message is published to Test-SNS, Test-SQS will receive a Message.

"OR"

2. Cross Account S3 Cross-Region-Replication
Cross-region replication (CRR) is the automatic, asynchronous copying of objects across buckets in different AWS Regions.
Cross-region replication replicates newly created objects, object updates, and object deletions from a source bucket to a destination bucket in a different AWS Region.
Create the below resources in the respective AWS Accounts:

Create resources:
Account A - Source Bucket
Account B - Destination Bucket

Requirement: Perform the required configuration to enable CRR

### II. Perform Kubernetes deployment using minikube and add security best practices based on your knowledge & experience.  

Deploy a simple web application on kubernetes. You can use minikube on your local machine to perform this activity.
Ref: https://octoperf.com/blog/2019/09/05/kraken-kubernetes-ingress-nginx-frontend/#prerequisites
Ref: https://www.appvia.io/blog/tutorial-deploy-kubernetes-cluster

Please have point II handy before the interview call for us to validate your work. 

Note: Request you to complete the task and send the code within 3 working days.
FYI: Creation of AWS account is free and you can try this in your personal accounts.
Happy coding!
