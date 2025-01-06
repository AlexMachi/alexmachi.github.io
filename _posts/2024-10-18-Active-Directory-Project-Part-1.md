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

![Desktop View](/assets/img/2024-10-18-Active-Directory-Project-Part-1/NetworkDiagram.jpg){: width="972" height="589" .w-50}


## 2. Set up VirtualBox and install the required operating systems
---
Download VirtualBox for Windows hosts from Oracle's website. 

```powershell
C:\Users\username\Downloads> Get-FileHash .\VirtualBox-version-win.exe
```

### Windows Server 2022:

### Windows 10:

### Ubuntu:

### Kali Linux:
