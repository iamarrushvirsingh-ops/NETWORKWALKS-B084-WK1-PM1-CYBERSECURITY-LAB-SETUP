# NETWORKWALKS-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP
This is the week lab report of my tasks that i was assigned at my intern at Networkwalks 



# 🔐 [Cybersecurity Lab Environment Setup]
Building an isolated virtual lab for penetration testing and ethical hacking practice.


<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.2.15%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
</p>







## 📌 Project Overview
[This project focuses on setting up a virtual cybersecurity laboratory using VirtualBox and Kali Linux to create a controlled testing environment , alogn this I also experimented a little about virutal network and howw they work in different configurations . I also set up juice shop in dokcer running on ,y host os and also set up metasploitable and configured kali to be able to connnect with all .]

## 🎯 Objectives
* Install and configure VirtualBox.
* Import Kali Linux as a virtual machine.
* Create a private NAT Network.
* Take a snapshot of the current config of kali .

## ⚙️ Lab Configuration
| 🧩 Component | ⚙️ Configuration |
| --- | --- |
| 🖥️ Host OS | [Linux Mint] |
| 🧰 Hypervisor | [VirtualBox] |
| 🐉 Security OS | [Kali Linux] |
| 📡 Network Address | [10.0.2.15/24] |

## 🪜 Lab Setup Procedure
**Step 1. [Action, Install Hypervisor]**
[I donwloaded Virtual box and set it up . After which i added kali linux iso file into it which I had downloaded prior .]


**Step 2. [Action, Create NAT Network]**
[I configured the network at NAT network and set up my metasploitable also on this nat network , so not only can my kali talk to my host os and internet it can also talk to my other vm's .]


## 🔎 Lab Verification
| ✅ Test | 🧾 Command | 🎯 Expected Result |
| --- | --- | --- |
| 🌐 Check IP address | `ip a` | Correct Kali IP displayed |
| 📡 Test gateway | `ping 10.0.2.15` | Successful replies |

## 🐞 Problems Encountered & Solutions
* **Problem:** [Internet Connectivity failed after changing NAT config ]
* **Solution:** [How to set up different adapters and tested if they worked with all intends that i had with the lab setup .]

## 💡 What I Learned
1. **[Concept 1]:** [The difference between different network configurations like standard NAT and a NAT Network in VirtualBox.]
2. **[Concept 2]:** [ How to securely snapshot a VM before running Nmap scans.]

## 👤 Author
**Arrush Vir Singh**

Cybersecurity Intern | B.Tech IT Student at AKGEC

LinkedIn: https://www.linkedin.com/in/arrush-vir-singh-6b3328378/

GitHub: https://github.com/iamarrushvirsingh-ops 

## 📌 Project Information
Program: Cybersecurity at Networkwalks | Week: [1] | Project: [lab set up ]
