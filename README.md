# IT Homelab

![VMware](https://img.shields.io/badge/VMware-Virtualization-blue)
![Windows Server](https://img.shields.io/badge/Windows%20Server-2022-blue)
![Microsoft Azure](https://img.shields.io/badge/Microsoft-Azure-0078D4)
![Linux](https://img.shields.io/badge/Linux-System%20Administration-black)
![Microsoft 365](https://img.shields.io/badge/Microsoft%20365-Administration-purple)

## 📌 Overview

Welcome to my **IT Homelab** repository.

This project is a personal hands-on environment where I practice and document **system administration, virtualization, server management, cloud administration, Microsoft 365 administration, Linux, networking, troubleshooting, and automation**.

The goal of this homelab is to build practical IT infrastructure skills through real-world lab scenarios, configuration exercises, troubleshooting, and documentation.

---

## 🛠️ Technologies

### VMware

* VMware ESXi
* VMware vSphere
* Virtual Machines
* Virtual networking
* Datastore management
* Host configuration
* Resource management

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

### Microsoft 365 / Office Administration

* Microsoft 365 administration
* User account management
* Microsoft 365 services
* Microsoft Office applications
* License and access management
* Basic account troubleshooting
* Security and administration concepts

### Microsoft Azure

* Azure Virtual Machines
* Resource Groups
* Azure Virtual Networks
* Storage
* Microsoft Entra ID
* Identity and access management
* Azure administration
* Cloud infrastructure fundamentals

### Linux

* Linux installation and configuration
* User and group management
* File permissions
* Package management
* SSH
* Services and processes
* Networking
* System monitoring
* Bash commands and scripting

---

## 🎯 Learning Objectives

* Build practical **System Administration** experience
* Learn VMware virtualization and management
* Manage Windows Server 2022 environments
* Practice Active Directory administration
* Develop Microsoft 365 administration skills
* Learn Microsoft Azure cloud administration
* Build Linux system administration skills
* Improve networking and troubleshooting abilities
* Practice PowerShell and Bash automation
* Document technical work and solutions

---

## 🏗️ Lab Environment

The homelab is designed to simulate a small IT environment containing virtualized servers, Windows and Linux systems, Microsoft services, and cloud resources.

```text
                         INTERNET
                             │
                             │
                      ┌──────▼──────┐
                      │   NETWORK   │
                      │    ROUTER   │
                      └──────┬──────┘
                             │
                    ┌────────▼────────┐
                    │   VMware ESXi   │
                    │      Host       │
                    └────────┬────────┘
                             │
              ┌──────────────┼──────────────┐
              │              │              │
        ┌─────▼─────┐  ┌─────▼─────┐  ┌─────▼─────┐
        │ Windows   │  │   Linux   │  │   Other   │
        │ Server    │  │   Server  │  │    VMs    │
        │   2022    │  │           │  │           │
        └─────┬─────┘  └───────────┘  └───────────┘
              │
       ┌──────▼──────┐
       │     AD      │
       │     DNS     │
       │    DHCP     │
       └─────────────┘

                             │
                             │
                    ┌────────▼────────┐
                    │ Microsoft Azure │
                    │   Cloud Lab     │
                    └─────────────────┘
```

---

## 🧪 Labs and Projects

### VMware Labs

* Install and configure VMware ESXi
* Configure ESXi hostname and networking
* Create and manage virtual machines
* Configure virtual switches and networking
* Manage datastores
* Monitor host resources

### Windows Server Labs

* Install Windows Server 2022
* Configure a domain controller
* Create users and groups
* Configure DNS and DHCP
* Create and manage Group Policies
* Join client computers to the domain
* Practice server troubleshooting

### Microsoft 365 Administration Labs

* Create and manage users
* Manage Microsoft 365 accounts
* Explore administration portals
* Practice permissions and access management
* Manage Office applications
* Troubleshoot common user issues

### Azure Labs

* Create Azure Resource Groups
* Deploy Azure Virtual Machines
* Configure virtual networks
* Explore Microsoft Entra ID
* Manage cloud resources
* Practice identity and access management
* Explore hybrid infrastructure concepts

### Linux Labs

* Install Linux servers
* Configure users and groups
* Manage permissions
* Configure SSH
* Manage services
* Monitor system resources
* Practice Bash commands and scripts

---

## 📂 Repository Structure

```text
it-homelab/
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
│   ├── user-management/
│   ├── administration/
│   └── troubleshooting/
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
├── networking/
│
├── powershell/
│
├── documentation/
│
└── README.md
```

---

## 📝 Documentation

Each lab is documented with:

* **Objective**
* **Lab environment**
* **Requirements**
* **Configuration steps**
* **Commands used**
* **Screenshots**
* **Troubleshooting**
* **Problems encountered**
* **Solutions**
* **Lessons learned**

---

## 🔐 Security

This repository does **not** contain real passwords, API keys, private keys, or other sensitive credentials.

Any credentials, secrets, or environment-specific information used during the labs are stored separately and are never committed to GitHub.

---

## 📈 Skills Being Developed

Through this homelab, I am developing practical skills in:

**System Administration**
**Virtualization**
**Windows Server Administration**
**Active Directory**
**Microsoft 365 Administration**
**Microsoft Azure**
**Linux Administration**
**Networking**
**PowerShell**
**Bash**
**Troubleshooting**
**IT Documentation**

---

## 🚀 Project Status

This is an **ongoing learning project**. New labs, configurations, scripts, troubleshooting notes, and documentation will be added as I continue developing my IT infrastructure and cloud administration skills.

---

## 👨‍💻 Purpose

The purpose of this homelab is to gain **hands-on practical experience** with technologies commonly used in IT infrastructure and system administration environments.

I use this repository to **learn, build, troubleshoot, document, and improve** my technical skills.

> **Learn → Build → Break → Troubleshoot → Document → Improve**
