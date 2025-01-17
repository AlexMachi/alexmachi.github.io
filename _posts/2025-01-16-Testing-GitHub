---
title: Active Directory Project (Part 1)
date: 2024-10-17 12:00:00 -500
categories: [homelab, hardware]
tags: [draw.io,virtualbox,windows server 2020,windows 10,ubuntu server,kali linux]
image: 
  path: /assets/img/title/drawIO-virtualbox.png
---


## Active Directory Project Overview
---
In this guide, we will walk through the steps to set up a homelab that includes an Active Directory, a domain user, a Splunk server, and a penetration testing system using Kali Linux.

We will explore the workings of a domain environment by configuring a domain controller, adding a domain user, and creating group policies. Additionally, we will simulate a brute-force attack to generate telemetry, which will be ingested and analyzed using Sysmon and Splunk.

This setup will be achieved on a single Windows computer by utilizing VirtualBox to create a virtual environment for the homelab.

**Hardware Requirements:**

* Windows OS
* 16GB RAM
* 256GB Disk Space


## Active Directory Project (Part 1) Objectives
---
1\. Create a network diagram.

2\. Set up VirtualBox and install the following operating systems:

* Windows Server 2022
* Windows 10
* Ubuntu Server
* Kali Linux


## 1. Create a network diagram
---
A network diagram helps us visualize how data flows through the network. It also supports organizing and documenting network information, such as IP addresses and software distribution. The following network diagram was created in [draw.io](https://app.diagrams.net/){:target="_blank"}.

![Network Diagram](/assets/img/2024-10-18-Active-Directory-Project-Part-1/NetworkDiagram.jpg){: width="972" height="589" .w-50}


## 2. Set up VirtualBox and install the required operating systems
---
Download the VirtualBox installer for Windows hosts from [Oracle's official website](https://www.virtualbox.org/){:target="_blank"}. To ensure the downloaded installer has not been altered, we will verify its integrity by comparing the SHA256 checksum provided by Oracle with the SHA256 hash of the installer generated on our local system using PowerShell.

```powershell
C:\Users\User\Downloads> Get-FileHash .\VirtualBox-7.1.4-165100-Win.exe
```

![Checksum](/assets/img/2024-10-18-Active-Directory-Project-Part-1/Checksum.jpg){: width="972" height="589" .w-50}

Proceed with the VirtualBox installation by running the installer. The setup may prompt us to download any necessary software dependencies required by VirtualBox. After installing these dependencies, we can continue with the default settings to complete the installation. Once we click the 'Finish' button, VirtualBox should launch automatically.

![VM_001](/assets/img/2024-10-18-Active-Directory-Project-Part-1/VM_001.jpg){: width="972" height="589" .w-50}

### Windows 10:
Download the Windows 10 Media Creation Tool from [Microsoft's official website](https://www.microsoft.com/en-ca/software-download/windows10/){:target="_blank"}. This tool will create a Windows 10 ISO image file, which can be used to install Windows 10 on a virtual machine within VirtualBox.

Run the Windows 10 Media Creation Tool and follow the setup process. During the setup, you will be prompted to make the following selections:

1\. What do you want to do?
* **Create installation media (USB flash drive, DVD, or ISO file) for another PC.**

2\. Select language, architecture, and edition.
* **Use the recommended options for this PC.**

3\. Choose which media to use.
* **ISO file.**

![Win10 ISO](/assets/img/2024-10-18-Active-Directory-Project-Part-1/WindowsISO.jpg){: width="972" height="589" .w-50}

With the Windows 10 ISO image file now created and saved on our system, we will open VirtualBox and click 'New' to begin configuring our Windows 10 virtual machine.

![VM_W10_001](/assets/img/2024-10-18-Active-Directory-Project-Part-1/VM_W10_001.jpg){: width="972" height="589" .w-50}

Virtual Machine installation will require configuration settings:
* 4GB RAM
* 1 CPU Core
* 50GB Disk Space

![VM_W10_002](/assets/img/2024-10-18-Active-Directory-Project-Part-1/VM_W10_002.jpg){: width="972" height="589" .w-50}

Once we set up the configuration for the virtual machine, we are ready to start the virtual machine by clicking the start icon.

![VM_W10_003](/assets/img/2024-10-18-Active-Directory-Project-Part-1/VM_W10_003.jpg){: width="972" height="589" .w-50}

### Kali Linux:

### Windows Server 2022:




### Ubuntu Server:




