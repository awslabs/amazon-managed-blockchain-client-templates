# Amazon Managed Blockchain Client Templates

The Amazon Managed Blockchain Client Templates enables developers to easily launch client hosts on Amazon EC2 to interact with blockchain networks created by <a href="https://aws.amazon.com/managed-blockchain">Amazon Managed Blockchain</a>. Each template is an AWS CloudFormation template that provisions an Amazon EC2 instance and installs and configures client software to work with you Amazon Managed Blockchain resources.
 
## Features

1. Allows you to select the instance type used for your client host
2. Configures the client software with endpoint information your provide for your Amazon Managed Blockchain resources
3. Configures TLS encryption for the client
 

## Getting Started

Before creating your client host, you will need to create several resources:
  * The Amazon VPC and subnet, Amazon EC2 key pair, Amazon EC2 security group, and an IAM instance profile for the Amazon EC2 instance provisioned.
  * The Amazon VPC subnet for the Amazon EC2 instance must have connectivity to the internet, because it will download required libraries from the internet.
  * An Amazon Managed Blockchain network with a peer node to provide the endpoint information for the client configuration.
  
Load and run the AWS CloudFormation template in your account.

SSH to the newly created instance to use the client and interact with you Amazon Managed Blockchain resources.
 

## License Summary

This sample code is made available under a modified MIT license. See the LICENSE file.