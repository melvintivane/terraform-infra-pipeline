# Terraform Infra Pipeline

## How to get started?
- Create the GitHub Identity Provider in your AWS account 
- Create an IAM Role in your AWS account (S3 and DynamoDB minimum permission) 
- Create an S3 Bucket in your AWS account (Enable Bucket Versioning) 
- Create a table in DynamoDB in your AWS account (PartitionKey named "LockID") 
- Clone this repository
- Configure the workflow files 
- Ready! You are now enabled to deploy infrastructure on AWS with Terraform via pipeline 
 
:mag:Download the project and test it yourself in practice.

Developed by Melvin Tivane

### Referências

- [How to connect GitHub Actions to AWS](https://aws.amazon.com/blogs/security/use-iam-roles-to-connect-github-actions-to-actions-in-aws/)