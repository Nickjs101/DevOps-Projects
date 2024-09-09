Task:
Creating a bash script that automates the backup of specified directories to
a remote server or external drive. 
Include features like compression, encryption, 
and email notifications upon completion.

Solution:
This project automatically backup files from local directory to AWS S3 bucket.

Requirements:
AWS Account with S3 permission
aws cli installed on local
crontab for automation
for email:
SSMTP
Mailutils
Mutt
tar for compression
GNUPg for encryption

Process:
Note: Ensure that aws account is setup & install the neccessary tools
1. compress the files
2. encrypt the files
3. transfer the files to s3 bucket
4. send notifications