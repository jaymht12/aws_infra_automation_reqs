1. Specific use-case to implememt updating S3 object ACL where object owner is Account A & object resides in Account B
2. This script can also be used if object owner & object grantee both accounts are same
3. Recursively applies update on ACL at object level, directory level, root directory level

variables: 
1. profile_name: profile name found under ~/.aws/credentials file
2. region_name: aws_region
3. Bucket: s3_bucket
4. Prefix: directories under s3_bucket
