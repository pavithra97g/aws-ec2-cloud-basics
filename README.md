# Cloud Basics Using AWS EC2 (Free Tier)

## Task Objective
To understand basic cloud infrastructure concepts using AWS EC2 Free Tier.

## Tools Used
- AWS EC2 (Amazon Linux 2)
- Apache Web Server
- SSH

## Steps Performed
1. Created AWS Free Tier account
2. Launched EC2 instance (t2.micro)
3. Generated key pair and connected via SSH
4. Installed Apache web server
5. Configured security group inbound rules
6. Accessed web application using public IP
7. Stopped EC2 instance to avoid billing

## Architecture
```
User Browser
     |
 Public IP
     |
AWS EC2 (Amazon Linux)
     |
Apache Web Server
```

## Outcome
Successfully deployed a web server on AWS EC2 and understood cloud fundamentals.

## Screenshots
- `ec2.png` → EC2 instance running
- `EC2-connected.png` → SSH connection proof
- `EC2-Webpage-Test.png` → Apache test page accessed via public IP
- `security-Group.png` → Security group inbound rules
- `EC2-Stopped.png` → EC2 instance is stopped
