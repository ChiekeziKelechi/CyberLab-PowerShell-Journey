# CyberLab PowerShell Journey

## Project Overview

This repository documents my hands-on practice while learning Ubuntu Server, VirtualBox, Linux commands, SSH, Windows PowerShell, Git, and GitHub.

The aim of this project was to create an Ubuntu Server virtual machine, perform basic Linux administration tasks, generate SSH keys, learn Git workflow, and publish my work to GitHub.

---

# Step 1 – Create the Ubuntu Virtual Machine

I created a new Ubuntu Server virtual machine using VirtualBox. During the setup, I selected the Ubuntu Server ISO image, named the virtual machine CyberLab, and reviewed the VM configuration before creating it.

## Evidence

[VirtualBox Summary](https://github.com/ChiekeziKelechi/CyberLab-PowerShell-Journey/blob/master/23C366A2-40FD-4379-983D-55DC62BBCA25.jpeg?raw=true)

---

# Step 2 – Configure the Virtual Machine

During the setup process, I configured the virtual machine name, selected Ubuntu as the operating system, and created my administrator account.

Configuration details:
- Virtual Machine Name: CyberLab
- Hostname: CyberLab
- Username: LabAdmin

## Evidence

[Virtual Machine Name and Operating System](https://github.com/ChiekeziKelechi/CyberLab-PowerShell-Journey/blob/master/IMG_0403.jpeg?raw=true)

[Profile Configuration](https://github.com/ChiekeziKelechi/CyberLab-PowerShell-Journey/blob/master/IMG_0407.jpeg?raw=true)

---

# Step 3 – Boot and Log Into Ubuntu

After completing the installation, I started the Ubuntu Server virtual machine and logged in using my LabAdmin account.

The system successfully booted and generated SSH host key information.

## Evidence

[Ubuntu Boot Process](https://github.com/ChiekeziKelechi/CyberLab-PowerShell-Journey/blob/master/IMG_0408.jpeg?raw=true)

[Ubuntu Login](https://github.com/ChiekeziKelechi/CyberLab-PowerShell-Journey/blob/master/IMG_0409.jpeg?raw=true)

---

# Step 4 – Practice Basic Linux Commands

After logging into Ubuntu, I practiced basic Linux commands to understand the file system and gather system information.

Commands used:

pwd  
ls  
ls -la  
whoami  
hostname  
hostname -I  

These commands helped me identify my current directory, view files, verify my username, check the hostname, and display the server IP address.

## Evidence

[Linux File Commands](https://github.com/ChiekeziKelechi/CyberLab-PowerShell-Journey/blob/master/Screenshots/Screenshot%202026-07-27%20000243.png?raw=true)

[System Information](https://github.com/ChiekeziKelechi/CyberLab-PowerShell-Journey/blob/master/Screenshots/Screenshot%202026-07-27%20001053.png?raw=true)

---

# Step 5 – Create My Project Directory

I created a project directory called **myfirstproject**, navigated into it, verified my working directory, and created a test file.

Commands used:

mkdir myfirstproject  
cd myfirstproject  
pwd  
touch testrun.txt  
ls  

## Evidence

[Creating Project Directory](https://github.com/ChiekeziKelechi/CyberLab-PowerShell-Journey/blob/master/Screenshots/Screenshot%202026-07-27%20003636.png?raw=true)

---

# Step 6 – Generate an SSH Key Pair

I generated an ED25519 SSH key pair using ssh-keygen.

I also checked my `.ssh` directory and viewed my public key.

Commands used:

ssh-keygen  
ls -la ~/.ssh  
cat ~/.ssh/id_ed25519.pub  

During this process, I encountered a small command syntax error, corrected it, and continued successfully.

## Evidence

[SSH Key Generation](https://github.com/ChiekeziKelechi/CyberLab-PowerShell-Journey/blob/master/Screenshots/Screenshot%202026-07-27%20004006.png?raw=true)

---

# Step 7 – Windows PowerShell Practice

I switched to Windows PowerShell and created a new project folder called **CyberLab-PowerShell-Journey**.

Commands used:

pwd  
ls  
mkdir  
cd  

## Evidence

[PowerShell Project Directory](https://github.com/ChiekeziKelechi/CyberLab-PowerShell-Journey/blob/master/Screenshots/Screenshot%202026-07-27%20011540.png?raw=true)

---

# Step 8 – Git Version Control

I initialized Git, configured my Git identity, staged my files, and created my first commit.

Commands used:

git add .  
git config --global user.name  
git config --global user.email  
git commit -m "Initial CyberLab project documentation"  
git log  

I first received an "Author identity unknown" message. I then configured my Git username and email before successfully creating the commit.

## Evidence

[Git Configuration](https://github.com/ChiekeziKelechi/CyberLab-PowerShell-Journey/blob/master/Screenshots/Screenshot%202026-07-27%20020641.png?raw=true)

[Git Commit](https://github.com/ChiekeziKelechi/CyberLab-PowerShell-Journey/blob/master/Screenshots/Screenshot%202026-07-27%20020814.png?raw=true)

---

# Step 9 – Publish Project to GitHub

Finally, I connected my local Git repository to GitHub and pushed my project online.

Commands used:

git remote add origin  
git remote -v  
git push -u origin master  

After correcting the repository connection, the project was successfully uploaded to GitHub.

## Evidence

[GitHub Upload](https://github.com/ChiekeziKelechi/CyberLab-PowerShell-Journey/blob/master/Screenshots/Screenshot%202026-07-27%20023741.png?raw=true)

---

# Conclusion

# Conclusion

In this project, I successfully created and configured an Ubuntu Server virtual machine using VirtualBox, performed essential Linux system administration tasks, generated and managed SSH keys, practiced Windows PowerShell commands, used Git for version control, and published the completed project to GitHub.

This project demonstrates my ability to document technical work, troubleshoot issues, and use fundamental cloud and Linux tools that form the foundation of cloud engineering.

---
