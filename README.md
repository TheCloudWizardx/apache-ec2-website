# 🚀 Apache Website Deployment on AWS EC2

## 📖 Description
Deployed a static website on an AWS EC2 instance using Apache Web Server. This project demonstrates hands-on experience with cloud infrastructure, Linux server management, and web hosting fundamentals.

## 🛠️ Tech Stack
- ☁️ AWS EC2 (Ubuntu)
- 🌐 Apache2
- 🧱 HTML
- 🎨 CSS
- 🐧 Linux

## 🧩 Steps
1. 🚀 Launch an EC2 instance
2. 🔓 Allow port **80 (HTTP)** from anywhere in Security Group inbound rules
3. 🔑 Connect to the EC2 instance using SSH
4. 📦 Install Apache2 and start the service
5. 📁 Move `.html` files to `/var/www/html`
6. 🔄 Restart Apache2 service
7. 🌍 Access the website using the EC2 public IP

## 🎯 Outcome
The website is successfully hosted and accessible over the internet using Apache Web Server on AWS EC2.

## 📌 Future Improvements
- Add HTTPS using SSL/TLS
- Automate deployment using Ansible
- Implement CI/CD pipeline
