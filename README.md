# Cloudformation_S3
This template creates an S3 bucket, a KMS key, and an IAM user. The KMS key is used to encrypt objects stored in the S3 bucket, and the IAM user is given permissions to manage the KMS key. The bucket is configured to use KMS encryption by default for all objects stored in the bucket.

You can add the naming convention as per your requirement

To Run this file 
You can use this template by saving it to a file and then using the aws cloudformation create-stack command to create a new stack. You will need to provide a stack name and specify the path to the template file.