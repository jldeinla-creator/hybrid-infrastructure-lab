# Hybrid-infrastructure-lab
Personal IT homelab documenting hands-on projects in VMware virtualization, Windows Server 2022, Microsoft 365 administration, Azure cloud, Linux, networking, and system administration.

# Hybrid Infrastructure Homelab

## 📌 Project Overview

This project is a personal **IT Infrastructure Homelab** designed to build practical hands-on experience with virtualization, Windows Server administration, networking, and Microsoft Azure.

The environment combines **VMware virtualization**, **Windows Server 2022**, and **Microsoft Azure** to simulate a small enterprise IT infrastructure.

## 🎯 Project Objectives

* Learn and practice VMware ESXi administration
* Deploy and manage Windows Server 2022
* Configure Active Directory Domain Services
* Manage users, groups, and permissions
* Configure DNS and DHCP
* Practice Windows Server administration
* Develop PowerShell skills
* Learn Microsoft Azure administration
* Understand on-premises and cloud infrastructure
* Practice troubleshooting and documentation

## 🛠️ Technologies Used

| Technology          | Purpose                           |
| ------------------- | --------------------------------- |
| VMware ESXi         | Virtualization platform           |
| VMware vSphere      | Virtual infrastructure management |
| Windows Server 2022 | Server operating system           |
| Active Directory    | Identity and user management      |
| DNS                 | Name resolution                   |
| DHCP                | IP address management             |
| PowerShell          | Administration and automation     |
| Microsoft Azure     | Cloud infrastructure              |
| Networking          | Communication between systems     |

## 🏗️ Lab Architecture

```text
                    INTERNET
                       │
                       │
                ┌──────▼──────┐
                │   NETWORK   │
                │   / ROUTER  │
                └──────┬──────┘
                       │
                ┌──────▼──────┐
                │ VMware ESXi  │
                │    Host      │
                └──────┬──────┘
                       │
          ┌────────────┼────────────┐
          │            │            │
     ┌────▼────┐  ┌────▼────┐  ┌────▼────┐
     │ Windows  │  │ Windows  │  │  Other  │
     │ Server   │  │   VM     │  │   VMs   │
     │  2022   │  │          │  │          │
     └────┬────┘  └──────────┘  └──────────┘
          │
     ┌────▼──────┐
     │  Active   │
     │ Directory │
     │    DNS    │
     │    DHCP   │
     └───────────┘

                       │
                       │ Cloud
                       ▼
                ┌──────────────┐
                │   Microsoft  │
                │    Azure     │
                └──────────────┘
```

## 🧪 Labs and Projects

### 1. VMware ESXi

* Install VMware ESXi
* Configure ESXi hostname
* Configure networking
* Create virtual machines
* Configure datastores
* Manage virtual machines
* Monitor host resources

### 2. Windows Server 2022

* Install Windows Server 2022
* Configure server networking
* Configure hostname
* Configure static IP address
* Install server roles
* Manage local users and groups

### 3. Active Directory

* Install Active Directory Domain Services
* Create a new domain
* Create organizational units
* Create users and groups
* Join Windows clients to the domain
* Manage user accounts
* Reset passwords and unlock accounts

### 4. DNS and DHCP

* Configure DNS
* Create DNS records
* Configure DHCP
* Create DHCP scopes
* Configure IP address reservations
* Troubleshoot DNS and network connectivity

### 5. PowerShell

* Basic PowerShell commands
* User administration
* System administration
* Active Directory management
* Automation scripts

### 6. Microsoft Azure

* Create Azure resources
* Create Resource Groups
* Deploy Azure Virtual Machines
* Configure Azure networking
* Explore Microsoft Entra ID
* Practice cloud administration

## 📂 Repository Structure

```text
hybrid-infrastructure-lab/
│
├── vmware/
│   ├── esxi/
│   ├── networking/
│   └── virtual-machines/
│
├── windows-server-2022/
│   ├── active-directory/
│   ├── dns/
│   ├── dhcp/
│   └── group-policy/
│
├── azure/
│   ├── virtual-machines/
│   ├── networking/
│   └── entra-id/
│
├── powershell/
│
├── networking/
│
├── documentation/
│
└── README.md
```

## 📚 What I Am Learning

Through this project, I am developing practical knowledge in:

* System Administration
* Virtualization
* Windows Server Administration
* Active Directory
* Networking
* PowerShell
* Cloud Administration
* Azure
* Troubleshooting
* IT Documentation

## 📸 Documentation

Each lab will include documentation such as:

* Lab objective
* Environment and requirements
* Configuration steps
* Commands used
* Screenshots
* Troubleshooting steps
* Problems encountered
* Solutions
* Lessons learned

## 🚀 Project Status

This is an ongoing project. New labs, configurations, documentation, and automation scripts will be added as I continue learning.

## 👨‍💻 Purpose

The purpose of this homelab is to gain **hands-on experience with real-world IT infrastructure** and build a practical portfolio for a career in **System Administration and IT Infrastructure**.

---

**Learn → Build → Troubleshoot → Document → Improve**
