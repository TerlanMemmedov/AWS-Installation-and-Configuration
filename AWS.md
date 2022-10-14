Downloading AWS CLI on Ubuntu
```
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
```
<br />
<br />


> If you get curl error
```
sudo apt install curl
```
<br />
<br />


Unzip downloaded AWS file
```
unzip awscliv2.zip
```
<br />
<br />


> If you get unzip error
```
sudo apt install unzip
```
<br />
<br />


Installing AWS CLI
```
sudo ./aws/install
```
<br />
<br />


Checking the version of AWS CLI
```
aws --version
```
<br />
<br />


AWS CLI Configuration
```
aws configure
```
<br />
<br />


Get the list of your EC2 instances
```
aws ec2 describe-instances
```
<br />
<br />


Get the list of light sail server details
```
aws lightsail get-bundles
```
<br />
<br />


Get the S3 bucket list
```
aws s3 ls
```
<br />
<br />


For deleting your credentials from Ubuntu. The Example has shown in the below
```
aws iam delete-access-key --access-key-id YOUR_ACCESS_KEY_ID --user-name YOUR_IAM_USERNAME
```
```
- aws iam delete-access-key --access-key-id AKIAV4DDWUFVJSTNHHWJ --user-name Kyle
```
