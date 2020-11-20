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


