# Ubuntu Server Installation Lab (VirtualBox)

## Objective

The objective of this lab was to install and configure an Ubuntu Server virtual machine using VirtualBox as the foundation of my cybersecurity homelab environment.

This lab marks the transition from setup tasks into hands-on system administration and Linux fundamentals.

---

## Environment

- Host OS: Windows
- Virtualization Software: VirtualBox
- Guest OS: Ubuntu Server (ISO installation)
- RAM Allocated: 4 GB
- CPU: 2 cores
- Storage: 30 GB (Dynamic)
- Network Mode: NAT

---

## Lab Steps

### 1. VirtualBox Installation
Installed VirtualBox to enable virtualization on my Windows system.

---

### 2. Ubuntu Server ISO Download
Downloaded the official Ubuntu Server ISO from the Ubuntu website.

---

### 3. Virtual Machine Creation
Created a new virtual machine with the following configuration:
- Name: Ubuntu-Server-Lab
- Type: Linux
- Version: Ubuntu (64-bit)

Allocated system resources:
- 4 GB RAM
- 2 CPU cores
- 30 GB dynamically allocated storage

---

### 4. ISO Attachment
Attached the Ubuntu Server ISO file to the virtual machine as a bootable installation medium.

---

### 5. Installation Process
Booted the virtual machine and launched the Ubuntu Server installation process.

Configured:
- Language and keyboard settings
- User account creation
- System hostname
- Disk setup

---

## Issues Encountered

### 1. ISO File Misunderstanding
Initially attempted to open the ISO file directly in Windows, but learned that ISO files are installation media and must be used inside a virtual machine.

---

### 2. Virtual Machine Setup Confusion
Experienced confusion regarding VM creation flow and VirtualBox configuration, but resolved by rechecking settings and completing setup correctly.

---

## Key Learnings

- Understanding of virtualization concepts (Host vs Guest OS)
- ISO files function as bootable installation media
- Basic VirtualBox configuration and VM setup
- Importance of structured troubleshooting and documentation

---

## Outcome

Successfully created and configured an Ubuntu Server virtual machine, establishing the foundation for future Linux and cybersecurity labs.

---

## Next Steps

- Learn Linux command-line navigation
- Practice file system operations
- Learn user and permission management
- Begin networking fundamentals
