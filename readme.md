Specific use-case to implememt updating S3 object ACL where object owner is Account A & object resides in Account B
This script can also be used if object owner & object grantee both accounts are same
Recursively applies update on ACL at object level, directory level, root directory level

variables: 
profile_name: profile name found under ~/.aws/credentials file
region_name: aws_region
Bucket: s3_bucket
Prefix: directories under s3_bucket
