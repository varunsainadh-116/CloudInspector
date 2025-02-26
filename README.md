## CloudResource Auditor
CloudResource Auditor is a shell script designed to automate the process of listing all active resources within an AWS account. 
By leveraging the AWS Command Line Interface (CLI), this tool provides users with a comprehensive inventory of their cloud infrastructure, aiding in efficient monitoring and management.

## Supported Services
The script currently supports the following AWS services:

1. Amazon Elastic Compute Cloud (EC2)
2. Amazon Relational Database Service (RDS)
3. Amazon Simple Storage Service (S3)
4. Amazon CloudFront
5. Amazon Virtual Private Cloud (VPC)
6. AWS Identity and Access Management (IAM)
7. Amazon Route 53
8. Amazon CloudWatch
9. AWS CloudFormation
10. AWS Lambda
11. Amazon Simple Notification Service (SNS)
12. Amazon Simple Queue Service (SQS)
13. Amazon DynamoDB
14. Amazon Elastic Block Store (EBS)

## Usage
To execute the script, use the following command:
   ```commandline
      ./cloud_resource_lister.sh <aws_region> <aws_service>
   ```
-  ```<aws_region>```: Specify the AWS region (e.g., us-east-1).
-  ```<aws_service>```: Specify the AWS service (e.g., ec2).
