# Terraform-App1

This app simply Creates and Launches an application using terraform on aws

## Usage


```
Let’s first see the things we are going to do by terraform for launching a simple application

Prerequisites- Knowledge of ec2, s3, ebs, terraform and cloudfront.

1.Create the key and security group which allow the port 80.
2. Launch EC2 instance.
3. In this Ec2 instance use the key and security group which we have created in step 1.
4. Launch one Volume (EBS) and mount that volume into /var/www/html
5. Developer have uploaded the code into github repo also the repo has some images.
6. Copy the github repo code into /var/www/html
7. Create S3 bucket, and copy/deploy the images from github repo into the s3 bucket and change the permission to public readable.
8 Create a Cloudfront using s3 bucket(which contains images) and use the Cloudfront URL to update in code in /var/www/html


First you have to configure your system to run aws cli and then tell in the code to use your this account
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
