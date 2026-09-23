# IT Infrastructure Homelab

![VMware](https://img.shields.io/badge/VMware-Virtualization-blue)
![Windows Server](https://img.shields.io/badge/Windows%20Server-2022-blue)
![Microsoft 365](https://img.shields.io/badge/Microsoft%20365-Administration-purple)
![CCNA](https://img.shields.io/badge/Cisco-CCNA-red)
![Azure](https://img.shields.io/badge/Microsoft-Azure-0078D4)
![Linux](https://img.shields.io/badge/Linux-System%20Administration-black)

## 📌 Overview

Welcome to my **IT Infrastructure Homelab** repository.

This is a personal hands-on lab environment where I practice and document **system administration, virtualization, networking, Windows Server administration, Microsoft 365 administration, cloud computing, Linux administration, troubleshooting, and automation**.

The purpose of this homelab is to build practical technical skills through real-world lab scenarios, configuration exercises, troubleshooting, and technical documentation.

---

## 🛠️ Technologies & Areas of Study

### VMware

* VMware ESXi
* VMware vSphere
* Virtual machine deployment
* Virtual networking
* Datastore management
* Host configuration
* Resource management
* VM snapshots and administration

### Windows Server 2022

* Windows Server installation and configuration
* Active Directory Domain Services
* User and group management
* DNS
* DHCP
* Group Policy
* File and folder permissions
* Remote administration
* Server troubleshooting

### Microsoft Office / Microsoft 365 Administration

* Microsoft 365 administration
* User and account management
* Microsoft Office applications
* License and access management
* Basic Microsoft 365 troubleshooting
* Identity and access concepts
* Administrative portal practice

### CCNA / Networking

* Networking fundamentals
* OSI and TCP/IP models
* IPv4 and IPv6
* Subnetting
* VLANs
* Trunking
* Routing
* Switching
* Static routing
* DHCP
* DNS
* NAT
* Network troubleshooting
* Cisco IOS fundamentals
* Packet Tracer labs

### Microsoft Azure

* Azure Resource Groups
* Azure Virtual Machines
* Azure Virtual Networks
* Storage
* Microsoft Entra ID
* Identity and access management
* Network configuration
* Cloud administration
* Hybrid infrastructure concepts

### Linux

* Linux installation and configuration
* User and group management
* File permissions
* Package management
* SSH
* Services and processes
* Networking
* System monitoring
* Bash commands
* Bash scripting

---

## 🎯 Learning Objectives

* Build practical **System Administration** skills
* Develop strong networking fundamentals through **CCNA studies**
* Learn VMware virtualization and management
* Administer Windows Server 2022 environments
* Practice Active Directory administration
* Develop Microsoft 365 administration skills
* Learn Microsoft Azure cloud administration
* Build Linux system administration skills
* Improve troubleshooting and problem-solving abilities
* Practice PowerShell and Bash
* Document technical projects and solutions

---

## 🏗️ Homelab Architecture

```text
                              INTERNET
                                  │
                                  │
                         ┌────────▼────────┐
                         │     ROUTER /    │
                         │     FIREWALL    │
                         └────────┬────────┘
                                  │
                           ┌──────▼───────┐
                           │   NETWORK    │
                           │   SWITCH     │
                           └──────┬───────┘
                                  │
                         ┌────────▼────────┐
                         │   VMware ESXi   │
                         │      HOST       │
                         └────────┬────────┘
                                  │
                ┌─────────────────┼─────────────────┐
                │                 │                 │
         ┌──────▼──────┐   ┌──────▼──────┐   ┌──────▼──────┐
         │ Windows     │   │    Linux    │   │    Other    │
         │ Server 2022 │   │    Server   │   │     VMs     │
         └──────┬──────┘   └─────────────┘   └─────────────┘
                │
        ┌───────┼────────┐
        │       │        │
      ┌─▼─┐   ┌─▼─┐   ┌─▼──┐
      │ AD │   │DNS│   │DHCP│
      └───┘   └───┘   └────┘

                                  │
                                  │ Cloud
                                  ▼
                         ┌─────────────────┐
                         │ Microsoft Azure │
                         │    Cloud Lab    │
                         └─────────────────┘
```

---

## 🧪 Labs & Projects

### VMware Labs

* Install and configure VMware ESXi
* Configure ESXi hostname
* Configure virtual networking
* Create and manage virtual machines
* Configure datastores
* Monitor host resources
* Practice VM administration

### Windows Server 2022 Labs

* Install Windows Server 2022
* Configure a domain controller
* Create users and groups
* Configure DNS
* Configure DHCP
* Create Group Policies
* Join client computers to the domain
* Manage permissions
* Troubleshoot server issues

### Microsoft 365 / Office Administration Labs

* Create and manage user accounts
* Explore Microsoft 365 administration
* Manage licenses and access
* Configure basic administrative settings
* Practice Microsoft Office administration
* Troubleshoot common user and account issues

### CCNA Networking Labs

* Create IP addressing plans
* Practice subnetting
* Configure VLANs
* Configure trunk ports
* Configure inter-VLAN routing
* Configure static routes
* Practice DHCP
* Configure basic NAT
* Troubleshoot network connectivity
* Practice Cisco IOS commands
* Build network simulations with Cisco Packet Tracer

### Azure Labs

* Create Resource Groups
* Deploy Azure Virtual Machines
* Configure Virtual Networks
* Configure storage resources
* Explore Microsoft Entra ID
* Practice identity and access management
* Manage Azure resources
* Explore hybrid cloud concepts

### Linux Labs

* Install Linux operating systems
* Create users and groups
* Configure file permissions
* Manage services
* Configure SSH
* Manage packages
* Configure networking
* Monitor system resources
* Practice Bash commands and scripting

---

## 📂 Repository Structure

```text
it-infrastructure-homelab/
│
├── vmware/
│   ├── esxi/
│   ├── vsphere/
│   ├── networking/
│   └── virtual-machines/
│
├── windows-server-2022/
│   ├── active-directory/
│   ├── dns/
│   ├── dhcp/
│   ├── group-policy/
│   └── file-services/
│
├── microsoft-365/
│   ├── administration/
│   ├── user-management/
│   └── troubleshooting/
│
├── ccna/
│   ├── networking-fundamentals/
│   ├── subnetting/
│   ├── switching/
│   ├── routing/
│   ├── vlan/
│   └── packet-tracer/
│
├── azure/
│   ├── virtual-machines/
│   ├── networking/
│   ├── entra-id/
│   └── storage/
│
├── linux/
│   ├── administration/
│   ├── networking/
│   ├── ssh/
│   └── bash/
│
├── powershell/
│
├── documentation/
│
└── README.md
```

---

## 📝 Lab Documentation

Each lab is documented with:

* **Objective**
* **Lab environment**
* **Requirements**
* **Configuration steps**
* **Commands and configurations**
* **Screenshots**
* **Troubleshooting steps**
* **Problems encountered**
* **Solutions**
* **Lessons learned**

---

## 🔐 Security

This repository does **not** contain real passwords, API keys, private keys, tokens, or other sensitive information.

Lab credentials and secrets are stored separately and are never committed to GitHub.

---

## 📈 Skills in Development

| Area            | Skills                                              |
| --------------- | --------------------------------------------------- |
| Virtualization  | VMware ESXi, vSphere, Virtual Machines              |
| Windows         | Windows Server 2022, AD, DNS, DHCP, Group Policy    |
| Microsoft 365   | User management, licensing, administration          |
| Networking      | CCNA, TCP/IP, VLANs, routing, switching, subnetting |
| Cloud           | Microsoft Azure, VMs, networking, Entra ID          |
| Linux           | Administration, SSH, permissions, services, Bash    |
| Automation      | PowerShell, Bash                                    |
| Troubleshooting | System, network, server, and user issues            |
| Documentation   | Lab guides, configurations, troubleshooting notes   |

---

## 🚀 Project Status

**Ongoing**

This homelab is continuously updated as I complete new labs, projects, configurations, scripts, and troubleshooting exercises.

---

## 👨‍💻 Purpose

This project is part of my journey toward developing a career in **IT Infrastructure and System Administration**.

My goal is to gain practical experience by building and managing a simulated IT environment covering **virtualization, Windows Server, Microsoft 365, networking, cloud infrastructure, and Linux**.

> **Learn → Build → Break → Troubleshoot → Document → Improve**
