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
1. install the neccessary tools
2. compress the files
3. encrypt the files
4. transfer the files to s3 bucket
5. send notifications