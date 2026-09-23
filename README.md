# 🖥️ IT Infrastructure & System Administration Homelab

Welcome to my **IT Infrastructure Homelab Portfolio**.

This repository documents my hands-on learning and practical projects in **VMware virtualization, Windows Server 2022, Microsoft 365/Office administration, CCNA networking, Microsoft Azure, and Linux system administration**.

The goal of this homelab is to build real-world IT infrastructure skills by **building, configuring, troubleshooting, documenting, and improving** different technologies in a controlled environment, while using **free, open-source, trial, and community resources whenever possible to keep costs as low as possible**.

All **documentation, configurations, procedures, notes, and screenshots** in this repository are based on my **own hands-on lab experience, testing, and troubleshooting**. The repository reflects my actual learning process, including the configurations I performed, problems I encountered, solutions I tested, and results I achieved.

---

## 👨‍💻 About This Portfolio

I use this homelab to strengthen my practical knowledge in **System Administration, IT Infrastructure, Networking, Virtualization, Cloud Computing, and Technical Support**.

Each project focuses on practical tasks that can be found in real IT environments, including server administration, network configuration, user management, virtualization, cloud resources, and troubleshooting.

**Learn → Build → Troubleshoot → Document → Improve**

# 🧪 Featured Lab Projects

## 1. VMware ESXi Homelab

**Objective:** Build and manage a virtualized server environment.

**Hands-on tasks:**

* Install VMware ESXi
* Configure ESXi hostname and networking
* Create virtual machines
* Configure virtual switches
* Manage datastores
* Allocate CPU and memory resources
* Monitor virtual machines
* Troubleshoot virtualization issues
## View Project →
---

## 2. Windows Server 2022 Lab

**Objective:** Build a Windows Server environment for system administration practice.

**Hands-on tasks:**

* Install Windows Server 2022
* Configure server networking
* Configure Active Directory
* Create users and groups
* Configure DNS
* Configure DHCP
* Create Group Policies
* Join client systems to the domain
* Manage permissions
* Troubleshoot server and user issues
## View Project →
---

## 3. Microsoft 365 / Office Administration Lab

**Objective:** Practice common Microsoft 365 administration and support tasks.

**Hands-on tasks:**

* Manage user accounts
* Explore Microsoft 365 administration
* Manage licenses and access
* Practice account administration
* Support Microsoft Office applications
* Troubleshoot common user and account issues
## View Project →
---

## 4. CCNA Networking Lab

**Objective:** Develop practical networking skills and strengthen CCNA fundamentals.

**Hands-on tasks:**

* Design IP addressing schemes
* Practice subnetting
* Configure VLANs
* Configure trunk links
* Configure routing
* Configure inter-VLAN routing
* Practice DHCP
* Configure basic NAT
* Troubleshoot connectivity
* Practice Cisco IOS commands
* Build network topologies using Cisco Packet Tracer
## View Project →
---

## 5. Microsoft Azure Lab

**Objective:** Develop practical cloud administration skills.

**Hands-on tasks:**

* Create Resource Groups
* Deploy Azure Virtual Machines
* Configure Virtual Networks
* Configure storage resources
* Explore Microsoft Entra ID
* Practice identity and access management
* Manage Azure resources
* Explore hybrid cloud concepts
# View Project →
---

## 6. Linux Administration Lab

**Objective:** Develop practical Linux system administration skills.

**Hands-on tasks:**

* Install and configure Linux
* Create and manage users
* Manage groups
* Configure file permissions
* Install and manage packages
* Configure SSH
* Manage services
* Monitor system resources
* Configure networking
* Practice Bash commands and scripting
## View Project →
---

# 🏗️ Homelab Architecture
```text
                              INTERNET (ISP)
                                  │
                                  │
                         ┌────────▼─────────┐
                         │ Router / Modem   │
                         └────────┬─────────┘
                                  │
                    ┌─────────────▼───────────────┐
                    │ Personal Desktop / Laptop   │
                    └─────────────┬───────────────┘
                                  │
                    ┌─────────────▼─────────────┐
                    │ VMware Workstation Pro    │
                    └─────────────┬─────────────┘
                                  │
                          ┌───────▼────────┐
                          │   VMware ESXi  │
                          │   Virtual Host │
                          └───────┬────────┘
                                  │
               ┌──────────────────┼──────────────────┐
               │                  │                  │
        ┌──────▼──────┐    ┌──────▼──────┐    ┌──────▼──────┐
        │ Windows     │    │    Linux    │    │    Other    │
        │ Server 2022 │    │   Server    │    │     VMs     │
        └──────┬──────┘    └─────────────┘    └─────────────┘
               │
         ┌─────┼─────┐
         │     │     │
        ┌▼┐   ┌▼┐   ┌▼┐
        │AD│   │DNS│   │DHCP│
        └─┘   └──┘   └────┘


                         INTERNET / CLOUD
                                  │
                         ┌────────▼────────┐
                         │ Microsoft Azure │
                         │    Cloud Lab    │
                         └─────────────────┘
```

---

# 📂 Repository Structure

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
│   └── administration/
│
├── microsoft-365/
│   ├── administration/
│   ├── user-management/
│   └── troubleshooting/
│
├── ccna/
│   ├── fundamentals/
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

# 📚 Project Documentation

Each lab or project is documented using a consistent structure:

```text
01 - Objective
02 - Environment
03 - Requirements
04 - Configuration
05 - Commands Used
06 - Testing
07 - Troubleshooting
08 - Results
09 - Lessons Learned
```

Where appropriate, projects include **screenshots, diagrams, configuration files, scripts, and troubleshooting notes**.

---

# 📊 Skills Demonstrated

| Area                   | Skills                                                     |
| ---------------------- | ---------------------------------------------------------- |
| Virtualization         | VMware ESXi, vSphere, Virtual Machines                     |
| Windows Administration | Windows Server 2022, AD, DNS, DHCP, Group Policy           |
| Microsoft 365          | User management, licensing, administration, support        |
| Networking             | CCNA fundamentals, VLANs, routing, switching, subnetting   |
| Cloud                  | Microsoft Azure, VMs, networking, Entra ID                 |
| Linux                  | System administration, SSH, permissions, services, Bash    |
| Automation             | PowerShell, Bash, scripting                                |
| Troubleshooting        | Server, network, account, and connectivity troubleshooting |
| Documentation          | Technical notes, lab guides, diagrams, troubleshooting     |

---

# 🔐 Security

For security and privacy:

* No real passwords are stored in this repository.
* No API keys or access tokens are committed.
* No private keys or sensitive credentials are included.
* Lab examples use fictional or non-sensitive information.
* Secrets are stored separately from the Git repository.

---

# 🚀 Project Status

**🟢 Ongoing**

This portfolio is continuously updated as I complete new labs, projects, configurations, scripts, and troubleshooting exercises.

---

# 🎯 Career Focus

This homelab is part of my ongoing development toward a career in **System Administration and IT Infrastructure**.

My focus is on gaining practical experience with:

**Virtualization → Windows Administration → Networking → Microsoft 365 → Azure → Linux → Automation**

The projects in this repository represent my hands-on learning and provide a documented record of the technical skills I am developing.

---

## 📌 Note

This is a **learning and portfolio project**. Some environments are simulated or built specifically for practice and may differ from production enterprise environments.
