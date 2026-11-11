 # Linux-Based Web Server Deployment on AWS EC2

## Project Overview

This project demonstrates the setup and deployment of an Apache web server on an Amazon Linux EC2 instance. The project includes EC2 instance configuration, SSH access, Security Group configuration, Apache installation, Linux file permission management, and basic server troubleshooting.

## AWS Services Used

- Amazon EC2
- Amazon Linux
- Apache HTTP Server
- AWS Security Groups
- SSH
- Linux

## Project Implementation

1. Launched an Amazon Linux EC2 instance.
2. Configured SSH access to connect to the EC2 instance.
3. Configured Security Group inbound rules to allow SSH (Port 22) and HTTP (Port 80) traffic.
4. Installed and configured the Apache HTTP server.
5. Started and enabled the Apache service.
6. Created and deployed a basic HTML webpage.
7. Managed Linux file permissions.
8. Checked Apache service status and resolved basic server issues.
9. Tested the hosted webpage through a web browser using the EC2 public IP address.

## Architecture

![Linux-Based Web Server Deployment on AWS EC2](./architecture.png)

## Project Flow

User / Browser → Internet → AWS EC2 (Amazon Linux) → Apache Web Server → Hosted Webpage

The user accesses the hosted webpage through a web browser using the EC2 public IP address. Security Groups control incoming SSH and HTTP traffic, while Apache handles web requests and serves the webpage.

## Skills Demonstrated

- AWS Cloud Computing
- Amazon EC2
- Amazon Linux
- Linux System Administration
- Apache Web Server
- SSH Remote Access
- Security Group Configuration
- Linux File Permissions
- Server Troubleshooting
- Web Server Deployment

## Project Outcome

- Successfully deployed an Apache web server on Amazon Linux EC2.
- Configured SSH access for remote server management.
- Configured Security Groups to allow SSH and HTTP traffic.
- Hosted a basic webpage and accessed it through a web browser.
- Managed Linux file permissions and resolved basic server issues.
- Gained practical experience in AWS EC2 and Linux server administration.
