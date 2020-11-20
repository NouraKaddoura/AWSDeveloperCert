# AWS Developer Exam - Certification

Cost: $150
Needed to pass: 720/1000

Domain 1: Deployment: 22%
Domain 2: Security: 26%
Domain 3: Development with AWS Services: 30%
Domain 4: Refactoring: 10%
Domain 5: Monitoring & Troubleshooting: 12%

What does IAM give you?

- Centralized control of your AWS Account
- Shared access to your AWS account
- Granular permissions
- Identify federation (including active directory, facebook, linkedin, etc)
- Multifactor AUthentication
- Provides temporary access for users/devices and services, as necessary
- Allows you to set up your own password rotation policy
- Integrates with many different AWS services
- Supports PCI DSS Compliance


## Critical Terms

1. **Users** - End Users (think people)
2. **Groups** - Collection of users under one set of permissions
3. **Roles** - You can create roles and can then assign them to AWS resources 
4. **Policies** - document that defines one (or more) permissions


## Identity Access Management Lab

https://nourakaddouradevelopercert.signin.aws.amazon.com/console


IAM is global
Practice creating groups, policies, users. (Policy Documents)
Deny will override all Allows

IAM is unerversal. It does not apply to regions at this time. The root account is simply the account created when first setup your aws account. It has complete admin access. 

new users have no permissions when first created. 

New users are assigned access key ID & secret access keys when first created. not the same as password you cannot use it to access aws console. 

Only get to view the file for access keys one time - when you create them.

Always set up multifactor authentication (MFA) on your root account


AWS Certified Developer - Associate 2020 - Beginner Guide to IAM Quiz


## Chapter 2: Beginners Guide to IAM

## Which of the following is NOT a feature of IAM?

1. Integrates with existing active directory account allowing single sing on

2.Fine-grained access control to AWS resources

3. Centralized control of your AWS Account

**4. Allows you to set up biometric authentication, so that no passwords are required - Answer**

## AWS recommends that EC2 instances have credentials stored on them so that the instances can access other resources (such as S3 buckets).
False

## In AWS, What is IAM used for?

1. secure VPN access to AWS
2. Managing access to AWS services
3. Assigning permissions to allow and deny access to AWS resources
4. Creating and managing users and groups

**Answer: 2,3, & 4**

## Which IAM entity can you use to delegate access to your AWS resources to users, groups or services?
**1. IAM Role - Answer**
2. IAM User
3. IAM Web Identity Federation
4. IAM Group

## What is an IAM Policy?

1. A file containing a users private ssh key
2. the policy which determines how your aws bill will be paid
**3. A JSON document which defines one or more permissions - Answer**
4. A CSV file which contains a users accss key and secret access key. 

## WHich is the best way to enable your EC2 instance to read files in an s3 bucket?
1. Create an IAM role with read-access to S3 and assign the role to the EC2 instance

## Which statement best describes IAM?

1. IAM allows you to manage users, groups, and roles and their corresponding level of access to the AWS Platform.


## Chapter 3: Beginnes GUide to EC2

## Chapter 4: S3

## Chapter 5: Intorduction to Serverless Computing

## Chapter 6: DynamoDB

## Chapter 7: KMS and Encryption on AWS

## Chapter 8: Other AWS Services

## Chapter 9: Developer Theory

## Chapter 10: Advanced IAM

## Chapter 11: Monitoring

## Chapter 12: Updates based on Student Feedback

## Chapter 13:

