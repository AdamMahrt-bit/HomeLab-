## 📌 Overview

This project demonstrates the creation of a virtualized Linux server using Oracle VirtualBox and Ubuntu Server. The goal was to build a safe and isolated environment for learning Linux system administration, networking fundamentals, and web server deployment by installing and testing Nginx.
---
## 🛠️ Tools & Technologies

Oracle VirtualBox Manager

Ubuntu Server 24.04.3 LTS

Linux

Nginx
---
## ❓ Problem Statement

Running services directly on a personal workstation can be unreliable and risky. System misconfigurations or experimental changes may impact the main operating system.

By using virtualization, this project creates an isolated server environment that can be safely reset using snapshots. This allows for hands-on learning and experimentation without affecting the host machine.
---
##🎯 Project Objectives

Create a Linux server in a virtualized environment

Practice Linux system administration and package management

Deploy and test a web server using Nginx

Understand basic networking between host and virtual machine
---
##⚙️ Implementation Steps & Purpose
#Step 1: Acquired a home desktop to run the server

-Provides dedicated hardware for hosting the virtual machine

-Ensures stability without affecting my main workstation


#Step 2: Installed VirtualBox and created a new virtual machine

-Enables virtualization and system isolation

-Simulates a real server environment for learning


#Step 3: Selected Linux as the operating system

-Linux is the industry standard for server environments

-Builds familiarity with command-line tools and system management


#Step 4: Allocated system resources (2GB RAM, 20GB storage, etc.)

Ensures the virtual machine runs efficiently

Introduces basic hardware resource planning


#Step 5: Attached the Ubuntu Server ISO

-Provides the bootable installation media for the operating system

-Mirrors real-world server provisioning practices


#Step 6: Installed Ubuntu Server on the virtual machine

-Establishes a functional Linux server environment

-Forms the foundation for future services and projects


#Step 7: Configured networking between host and server

-Allows communication between the primary computer and the virtual machine

-Introduces IP addressing and bridged networking concepts

Step 8: Updated the system

Ensures security and stability through the latest packages

Demonstrates proper system maintenance procedures

Step 9: Installed Nginx web server

Adds a real service to the server environment

Provides a platform for testing web hosting functionality

Step 10: Verified Nginx installation

Confirms the service is running correctly

Strengthens troubleshooting and validation skills

Step 11: Tested Nginx access from the primary computer

Confirms successful network connectivity

Demonstrates a working web server deployment

📚 Key Takeaways

Virtualization: Learned to configure and manage a Linux VM using VirtualBox

Linux System Administration: Gained experience with package updates, terminal commands, and system structure

Web Server Management: Installed and verified Nginx and served a basic webpage

Networking Basics: Understood how IP addressing and bridged networking allow access from another machine

✅ Final Outcome

A fully functional virtualized Ubuntu Server running Nginx, accessible from the host machine. This project provides a foundation for future home lab experiments involving additional services, security configurations, and cloud technologies.

🚀 Future Improvements

Configure firewall rules (UFW)

Add SSH remote access

Deploy a custom webpage

Implement snapshots and backup strategies

Explore Docker or cloud integration
