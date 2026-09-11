# NETWORKWALKS-EMMANUEL-B083E-WK1-PM1-CYBERSECURITY-LAB-SETUP
# 🔐 Cybersecurity Lab Environment Setup

### Building an isolated virtual lab for penetration testing and ethical hacking practice

![Skill](https://img.shields.io/badge/Skill-Cybersecurity-red) ![Ver](https://img.shields.io/badge/Ver-VirtualBox%20v7.2-blue) ![Kali Linux](https://img.shields.io/badge/Kali%20Linux-v2026.2-blue) ![Skill](https://img.shields.io/badge/Skill-Linux-black) ![Network](https://img.shields.io/badge/Network-10.0.0.0%2F24-green) ![Penetration Testing](https://img.shields.io/badge/Penetration%20Testing-red)

![Skill](https://img.shields.io/badge/Skill-Virtualization-red) ![GitHub](https://img.shields.io/badge/GitHub-black?logo=github) ![Kali Linux](https://img.shields.io/badge/Kali%20Linux-red) ![NetworkWalks](https://img.shields.io/badge/NetworkWalks-black) ![Ethical Hacking](https://img.shields.io/badge/Ethical%20Hacking-orange) ![Waqas Karim CCIE](https://img.shields.io/badge/Waqas%20Karim-CCIE-red)

---

## 📌 Project Overview

This project focuses on setting up a **virtual cybersecurity and penetration-testing laboratory** using **VirtualBox and Kali Linux**.

The purpose of the lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be performed safely and repeatedly.

The lab is configured on a **private NAT Network** so that additional machines can be added later and used as targets for **authorized security testing**.

---

## 🎯 Objectives

The main objectives of this project are to:

- Install and configure **VirtualBox**.
- Install/import **Kali Linux** as a virtual machine.
- Create a **private NAT Network** for the cybersecurity lab.
- Configure and verify **Kali Linux network settings**.
- Test **network connectivity**.
- Verify **DNS resolution**.
- Create a **clean VM snapshot** for recovery.
- Prepare an isolated environment for **penetration testing and ethical hacking practice**.
- Maintain **security and privacy** while documenting the laboratory.

---

## 🛠️ Key Tasks Completed

### ✅ 1. VirtualBox Installation

- Installed and configured Oracle VM VirtualBox.
- Verified the virtualization environment.
- Prepared VirtualBox for cybersecurity lab setup.

### ✅ 2. Kali Linux Setup

- Imported Kali Linux into VirtualBox.
- Configured the Kali Linux virtual machine.
- Verified successful boot and system operation.
- Prepared Kali Linux for security-testing activities.

### ✅ 3. Private NAT Network

Created a dedicated NAT Network for the cybersecurity laboratory.

**Network:**

```text
10.0.0.0/24

                    HOST COMPUTER
                         │
                         ▼
                  ┌─────────────┐
                  │  VirtualBox │
                  └──────┬──────┘
                         │
                         ▼
                PRIVATE NAT NETWORK
                    10.0.0.0/24
                         │
                  ┌──────┴──────┐
                  │             │
                  ▼             ▼
             ┌─────────┐   ┌───────────┐
             │  Kali   │   │  Future   │
             │  Linux  │   │ Target VM │
             │  VM     │   │           │
             └────┬────┘   └─────┬─────┘
                  │               │
                  └───────┬───────┘
                          ▼
                 AUTHORIZED SECURITY
                       TESTING

📚 Key Learnings

Through this hands-on project, I gained practical experience with:

🔹 Virtual machine networking
🔹 NAT vs. NAT Network
🔹 IP configuration
🔹 Network troubleshooting
🔹 DNS resolution
🔹 Linux networking commands
🔹 VM snapshots and recovery
🔹 Virtualization
🔹 Technical documentation
🔹 Security and privacy practices
🔹 Building an isolated penetration-testing environment
👨‍💻 Project Information

Project Name: Cybersecurity & Pentesting Lab Setup

Program: Cybersecurity Program

Batch: B083

Organization: Networkwalks

Virtualization Platform: Oracle VM VirtualBox

Operating System: Kali Linux

Lab Network: 10.0.0.0/24

Project Focus:

Cybersecurity | Networking | Linux | Virtualization | Ethical Hacking | Penetration Testing
🙏 Acknowledgement

A big thank you to Waqas Karim (CCIE) and the entire NETWORKWALKS team for their guidance and support throughout this learning journey.
👩‍💻 Author
Raashid Fazal Pathan

⚠️ Disclaimer

This project is intended strictly for educational purposes and authorized security testing.

Do not use the tools, techniques, or configurations described in this repository against systems without proper authorization.
