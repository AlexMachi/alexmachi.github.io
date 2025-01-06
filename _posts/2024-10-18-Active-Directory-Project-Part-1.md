---
title: Active Directory Project (Part 1)
date: 2024-10-17 12:00:00 -500
categories: [homelab, hardware]
tags: [draw.io,VirtualBox,Windows Server 2020,Windows 10,Ubuntu,Kali Linux]
image: 
  path: /assets/img/title/drawIO-virtualbox.png
---

## Active Directory Project Overview

In this guide, we will walk through the steps to set up a homelab that includes an Active Directory, a domain user, a Splunk server, and an attacker machine using Kali Linux.

We will explore the workings of a domain environment by configuring a domain controller, adding a domain user, and creating group policies. Additionally, we will simulate a brute-force attack to generate telemetry, which will be ingested and analyzed using Splunk and Sysmon.

This setup will be achieved on a single Windows computer by utilizing VirtualBox to create a virtual environment for the homelab.

**Hardware Requirements:**

* Windows OS
* 16GB RAM
* 256GB Disk Space

## Part 1 Objectives
1. Create a network diagram using draw.io.

2. Set up VirtualBox and install the following operating systems: Windows Server 2022, Windows 10, Ubuntu, and Kali Linux.

## 1. Create a network diagram

Creating a network diagram helps us visualize how data flows through the network. It also supports organizing and documenting network information, such as IP addresses.

![NetworkDiagram](/assets/img/2024-10-18-Active-Directory-Project-Part-1/NetworkDiagram.jpg)
_Network diagram using draw.io._

## 2. Set up VirtualBox and install operating systems

### Windows Server 2022:

### Windows 10:

### Ubuntu:

### Kali Linux: