AWS EC2 Static Website Deployment (Apache Linux Server)

📖 Overview
This project demonstrates how I deployed a static website on a cloud server using Amazon EC2.  
I configured a Linux-based virtual machine, installed and configured Apache, and deployed a custom HTML webpage accessible from the internet.

🔨 Technologies Used
- Amazon EC2 (AWS Cloud)
- Amazon Linux
- Apache HTTP Server (httpd)
- SSH (Secure Shell)
- Linux Command Line
- Security Groups (AWS Firewall)
- HTML/CSS

🎯 Project Goals
- - Launch a cloud-based virtual server (EC2)
- Securely connect via SSH
- Install and configure a web server (Apache)
- Deploy a custom HTML webpage
- Configure network access using AWS Security Groups

🪜 Steps Performed
1. Launched an EC2 instance using Amazon Linux
2. Connected to the instance using SSH key pair
3. Installed Apache web server (httpd)
4. Configured Security Group to allow HTTP (port 80)
5. Verified Apache was running and listening on port 80
6. Created and deployed a custom index.html file
7. Fixed file directory issues (/var/www/html) when needed
8. Tested website via public IP in browser

🧱 Key Challenges & Fixes
- Issue: Website not loading in browser  
  Fix: Opened HTTP port 80 in AWS Security Group

- Issue: Apache serving incorrect or missing files  
  Fix: Recreated /var/www/html directory and restored correct file permissions

- Issue: Directory errors when editing website files  
  Fix: Verified Apache DocumentRoot and corrected file structure

🌐 Outcome
Successfully deployed a live website accessible via public IP address using an EC2 instance.
