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
We will now download the VirtualBox installer for Windows hosts from [Oracle's website](https://www.virtualbox.org/){:target="_blank"}. To ensure the downloaded installer has not been altered, we will verify its integrity by comparing the SHA256 checksum provided by Oracle with the SHA256 hash of the installer generated on our local system using PowerShell.

```powershell
C:\Users\User\Downloads> Get-FileHash .\VirtualBox-7.1.4-165100-Win.exe
```

![Checksum](/assets/img/2024-10-18-Active-Directory-Project-Part-1/Checksum.jpg){: width="972" height="589" .w-50}

We will proceed with the VirtualBox installation by running the installer. The setup may prompt you to download any necessary software dependencies required by VirtualBox. After installing these dependencies, you can continue with the default settings to complete the installation. Once you click the 'Finish' button, VirtualBox should launch automatically.

### Windows Server 2022:

### Windows 10:
We will first download Windows 10 media creation tool from Microsoft's website. The media creation tool will allow us to create a Windows 10 ISO image file in order for us to install it on our virtual machine inside of VirtualBox.



### Ubuntu Server:

### Kali Linux:
