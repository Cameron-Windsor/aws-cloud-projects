# 02 - Amazon EC2 Web Server

**Status:** Completed

## Project Overview

In this lab, I launched an Amazon EC2 instance running Amazon Linux and configured it to host a basic Apache web server. I used EC2 configuration options such as an AMI, instance type, key pair, networking, storage, security groups, and user data.

## AWS Services & Technologies

- Amazon EC2
- Amazon Linux
- Security Groups
- Amazon Machine Images (AMI)
- Apache HTTP Server
- Bash / EC2 User Data
- IPv4 networking

## What I Built

I created a virtual server in AWS and used a startup script to automatically:

```bash
#!/bin/bash
yum update -y
yum -y install httpd
systemctl enable httpd
systemctl start httpd
echo '<html><h1>Hello World!</h1></html>' > /var/www/html/index.html
```

The script updated the server, installed Apache, enabled it at startup, started the service, and created a basic web page.

## Validation

I confirmed that:

- The EC2 instance launched successfully.
- The instance reached a running state.
- EC2 status checks passed.
- The web server responded through the instance's public IPv4 address.
- The browser displayed the expected **Hello World!** page.

## Skills Demonstrated

- Provisioning cloud compute resources
- Linux server initialization
- Bash automation
- Security group configuration
- Basic web hosting
- Testing and validating a deployment
- AWS troubleshooting

## Screenshots

Screenshots in this project show the EC2 instance launch, running instance state, and the final working web page.

## What I Learned

This lab helped me understand how EC2 combines compute, operating system images, networking, storage, access controls, and startup automation to create a usable cloud server.
