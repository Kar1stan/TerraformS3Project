# TerraformS3Project
Terraform project using AWS S3 and DynamoDB,creating remote backend for terraform.tfstate file.

## 💻 Topics

Integrated with:

- [x] https://aws.amazon.com/
- [x] https://www.terraform.io/
      
## 💻 Pre-requisites

Before you use this project you need to have Terraform installed in your computer and have an account on AWS,and export AWS Access Keys to your terminal.
You also need to first create S3 bucket commenting backend "s3" in terraform.tf file,and then uncomment and run  the application.

### Git clone
This will clone the project,install Terraform which is required to run the test.
```
$ git clone https://github.com/Kar1stan/TerraformS3Project.git
$ cd TerraformS3Projec
```

## 🚀 Run the project: 
If you want run the project open the terminal and run: 
```
$ export AWS_ACCESS_KEY_ID=45trEayUUu1(example)
$ export AWS_SECRET_ACCESS_KEY=45trEayUUu1(example)
$ terraform init
$ terraform apply
(after uncommenting backend "s3" in terraform.tf)
$ terraform init
$ terraform apply

```
For further help or additional errors [here]([https://webdriver.io/docs/gettingstarted](https://developer.hashicorp.com/terraform/tutorials/aws-get-star))ted
