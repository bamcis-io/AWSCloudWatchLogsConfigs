# CloudWatch Logs Configs

This project contains a number of CloudWatch Logs configurations for Windows EC2 instances. They are provided both for the `EC2Config` service
based setup (Windows Server 2012 R2 and earlier) as well as the `SSMAgent` based setup (Windows Server 2016 and later).

## Table of Contents
- [Usage](#usage)

## Usage

For the SSM documents, create new SSM docs in AWS and paste in the json content. Then you can apply one of the documents to the desired EC2 instance.

For the EC2Config based configuration files, you can either  download the file into the EC2Config directory (`$env:ProgramFiles\Amazon\Ec2ConfigService\Settings`) or replace the contents of the `AWS.EC2.Windows.CloudWatch.json` file in that directory. 
