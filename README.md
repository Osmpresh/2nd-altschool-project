# 2nd-altschool-project
Name: Osimen Ebanehita Precious
Track: Cloud Engineering
School ID: ALT/SOE/024/0229


Provisioning a Linux Server with a Simple HTML Page using Apache2

Project Overview

This project demonstrates the process of provisioning a Linux server to host a simple HTML webpage using the Apache2 web server. It outlines the steps for configuring the server, installing necessary dependencies, and deploying the HTML page. This documentation serves as a guide for cloud engineering enthusiasts and students.

Author

Osimen Precious
Cloud Engineering Student, AltSchool Karatu '24

Prerequisites

A Linux-based server (e.g., Ubuntu).

SSH access to the server.

Basic knowledge of Linux command-line operations.

An active internet connection.

Tools and Technologies

Linux OS: Ubuntu 20.04 or later is recommended.

Apache2: Open-source web server software.

HTML: For creating the simple webpage.

SSH: Secure Shell for server access.

Steps to Provision the Server

1. Update and Upgrade the System

Run the following commands to ensure your server packages are up-to-date:

sudo apt update
sudo apt upgrade -y

2. Install Apache2

Install the Apache2 web server using the package manager:

sudo apt install apache2 -y

3. Start and Enable Apache2 Service

Start the Apache2 service and enable it to start on boot:

sudo systemctl start apache2
sudo systemctl enable apache2

4. Verify Apache2 Installation

Check if Apache2 is running by visiting the server's IP address in a web browser. You should see the default Apache2 welcome page.

5. Create a Simple HTML Page

Navigate to the Apache2 default web directory:

cd /var/www/html

Create an HTML file:

sudo nano index.html

Add the following content to the file:

<!DOCTYPE html>
<html>
<head>
    <title>Welcome to My Server</title>
</head>
<body>
    <h1>Hello from Osimen Precious!</h1>
    <p>This is a simple HTML page hosted on Apache2.</p>
</body>
</html>

Save and close the file.

6. Test the HTML Page

Access the server's IP address in a web browser. The HTML page you created should be displayed.

Troubleshooting

If the HTML page does not load, ensure the Apache2 service is running:

sudo systemctl status apache2

Check firewall settings to allow HTTP traffic:

sudo ufw allow 'Apache'

Conclusion

This project demonstrates how to provision a Linux server and deploy a simple HTML page using Apache2. It is a foundational skill for cloud engineering and serves as a stepping stone for more advanced server configurations and web hosting.

Osimen Precious Cloud Engineering Student, AltSchool Karatu '24

 **Deliverable**:

 IP Address: 54.151.116.24

 **Screenshot**
<img width="469" alt="Screenshot 2024-12-23 002313" src="https://github.com/user-attachments/assets/3c5365d1-f5e8-4910-a3e5-f1447511d350" />

 
