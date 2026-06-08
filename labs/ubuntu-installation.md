\# Ubuntu Server Installation Lab



\## Objective



Deploy an Ubuntu Server virtual machine using VirtualBox as the foundation of a cybersecurity homelab. The goal of this lab is to establish a Linux environment for learning system administration, networking, security fundamentals, and cybersecurity tools while documenting the installation process, troubleshooting steps, and lessons learned.



\---



\## Background



Prior to this lab, I had successfully:



\- Installed Git

\- Created a GitHub account

\- Created and structured a cybersecurity learning repository

\- Connected a local Git repository to GitHub

\- Learned basic Git commands

\- Established a documentation workflow



This lab represents the beginning of Phase 1 (Linux Foundations) in my cybersecurity learning roadmap.



\---



\## Lab Environment



\### Host System



\- Windows

\- Git Bash

\- GitHub Repository



\### Virtualization Platform



\- VirtualBox



\### Guest Operating System



\- Ubuntu Server LTS



\---



\## Learning Goals



By completing this lab I intended to:



\- Understand virtualization concepts

\- Learn the purpose of ISO files

\- Deploy a Linux server

\- Become comfortable working with virtual machines

\- Establish an environment for future cybersecurity labs

\- Practice technical documentation



\---



\# Concepts Learned



\## Virtualization



Virtualization allows multiple operating systems to run on a single physical computer.



\### Host Operating System



The operating system installed on the physical computer.



Example:



Windows



\### Guest Operating System



The operating system installed inside the virtual machine.



Example:



Ubuntu Server



\### Why Virtualization Matters



Virtualization allows:



\- Safe experimentation

\- Isolated testing environments

\- Multiple systems on one device

\- Easy recovery from mistakes



This is commonly used in cybersecurity, cloud computing, system administration, and software development.



\---



\## ISO Files



An ISO file is a complete disk image that contains installation media for an operating system.



Example:



ubuntu-24.04-live-server-amd64.iso



\### Initial Misunderstanding



I initially attempted to open the ISO file directly in Windows.



\### Lesson Learned



ISO files are not executable installers.



Instead, they are attached to a virtual machine and used as a bootable installation source.



\---



\# Installation Process



\## Step 1: Download Ubuntu Server



Downloaded the Ubuntu Server ISO from the official Ubuntu website.



Objective:



Obtain installation media for the guest operating system.



\---



\## Step 2: Attempted to Open ISO File



\### Issue Encountered



Windows SmartScreen prevented the file from opening.



\### Initial Assumption



I believed the ISO file should open like a normal installer.



\### What I Learned



Ubuntu Server ISO files are not intended to be launched directly from Windows.



The ISO serves as installation media that is mounted and booted through a virtual machine.



\### Resolution



Stopped attempting to open the ISO directly and proceeded with VirtualBox setup.



\---



\## Step 3: Install VirtualBox



Installed VirtualBox to provide a virtualization environment.



Purpose:



Create and run virtual machines.



\---



\## Step 4: Create Ubuntu Virtual Machine



Created a new virtual machine with the following configuration:



\### Name



Ubuntu-Server-Lab



\### Operating System



Linux

Ubuntu (64-bit)



\### Memory



4 GB RAM



\### CPU



2 Virtual CPUs



\### Storage



30 GB Dynamic Disk



\---



\## Step 5: Attach Ubuntu ISO



Selected the Ubuntu Server ISO as the startup disk for the virtual machine.



Purpose:



Allow the virtual machine to boot into the Ubuntu installation environment.



\---



\## Step 6: Start Virtual Machine



Booted the virtual machine.



Observed:



Ubuntu installer launched successfully.



\---



\## Step 7: Complete Ubuntu Installation



Configured:



\- Language

\- Keyboard layout

\- User account

\- Hostname

\- Storage settings



Completed operating system installation.



\---



\# Challenges and Troubleshooting



\## Challenge 1: SmartScreen Blocking Ubuntu ISO



\### Error



Windows SmartScreen prevented the ISO from opening.



\### Analysis



This occurred because Windows treated the ISO as a potentially unsafe downloaded file.



\### Root Cause



Misunderstanding of how ISO files are used.



\### Resolution



Learned that ISO files are mounted within VirtualBox and are not executed directly.



\### Lesson Learned



Understand the purpose of installation media before attempting to launch files.



\---



\## Challenge 2: Confusion Between Installer and Installation Media



\### Initial Understanding



Expected Ubuntu to install directly from the downloaded file.



\### Discovery



Ubuntu Server installation requires:



1\. Virtualization platform

2\. Virtual machine creation

3\. ISO attachment

4\. VM boot process



\### Lesson Learned



Operating systems require a boot process and installation environment.



\---



\## Challenge 3: Learning Host vs Guest Operating Systems



\### Initial Understanding



Limited understanding of virtualization architecture.



\### Lesson Learned



Host System:



Windows



Guest System:



Ubuntu Server



The guest operating system runs independently inside the virtual machine.



\---



\# Skills Developed



\## Technical Skills



\- Virtualization fundamentals

\- Ubuntu Server deployment

\- ISO file handling

\- Virtual machine creation

\- Operating system installation

\- Technical troubleshooting



\## Documentation Skills



\- Lab documentation

\- Recording lessons learned

\- Capturing troubleshooting steps

\- Maintaining project records



\---



\# Key Takeaways



1\. Virtual machines provide safe learning environments.

2\. Ubuntu Server serves as the foundation for future cybersecurity labs.

3\. ISO files are installation media, not traditional executable installers.

4\. Understanding host and guest operating systems is essential for virtualization.

5\. Troubleshooting installation issues improves technical understanding.

6\. Documentation is an important part of cybersecurity work.



\---



\# Future Applications



This Ubuntu Server virtual machine will be used for:



\- Linux command-line practice

\- User and permission management

\- Networking exercises

\- SSH configuration

\- Log analysis

\- Security monitoring

\- Nmap labs

\- Wireshark analysis

\- Security tool deployment



\---



\# Next Steps



\- Complete Ubuntu Server installation

\- Learn Linux navigation commands

\- Configure networking

\- Configure SSH

\- Document Linux fundamentals

\- Begin networking and security labs



\---



\## Lab Status



Status: In Progress



Phase: Linux Foundations (Phase 1)



Next Milestone: First Ubuntu Login and Linux Command-Line Basics





VM Name:

Ubuntu-Server-Lab



Host OS:

Windows



Guest OS:

Ubuntu Server



Configuration:

\- 4 GB RAM

\- 2 vCPUs

\- 30 GB Dynamic Storage

\- NAT Networking



Purpose:

Linux administration, networking fundamentals, cybersecurity labs, and homelab development.





\## VM Creation Issue (Resolved)



During VM creation, clicking "Finish" initially resulted in no visible VM being created. After retrying, the VirtualBox manager successfully registered the VM.



\### Outcome

The VM was successfully created and is now ready for Ubuntu Server installation.

