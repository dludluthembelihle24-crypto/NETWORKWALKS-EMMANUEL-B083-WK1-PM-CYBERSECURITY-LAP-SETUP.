# NETWORKWALKS-EMMANUEL-B083-WK1-PM-CYBERSECURITY-LAP-SETUP.

# 🛡️ Cybersecurity Home Lab | Kali Linux

## 📌 Project Overview

Welcome to my Cybersecurity Home Lab!

This project documents my journey into cybersecurity, focusing on setting up a virtual cybersecurity laboratory using Kali Linux and Oracle VirtualBox.

As a beginner in cybersecurity, I wanted to gain practical, hands-on experience with Linux environments, virtual machines, networking, and troubleshooting.

Setting up this lab was not without challenges. I encountered several technical issues during installation and configuration, which gave me an opportunity to research, troubleshoot, learn, and develop my problem-solving skills.

This repository documents my progress, the challenges I encountered, the solutions I explored, and the knowledge I gained along the way.

## 🖥️ Lab Environment

The following tools and technologies were used:

- *Operating System:* Windows (Host Machine)
- *Virtualisation Software:* Oracle VirtualBox
- *Guest Operating System:* Kali Linux
- *Architecture:* AMD64
- *Archive Extraction Tool:* 7-Zip
- *Documentation:* GitHub

## ⚙️ Challenges Encountered & Troubleshooting

### 1. Downloading Kali Linux

*Problem:*
While downloading the Kali Linux VirtualBox image, the download became stuck at 0 bytes per second. The file also appeared as an incomplete .crdownload file in Windows File Explorer.

*Troubleshooting:*
- Checked the download progress in Microsoft Edge.
- Paused and resumed the download.
- Monitored the download until it continued successfully.

*Outcome:* Successfully resumed the download.

### 2. Extracting the Kali Linux Archive

*Problem:*
After downloading Kali Linux, I struggled to extract the .7z archive correctly. Instead of seeing the expected virtual machine files, I initially encountered several folders and files.

*Solution:*
- Installed 7-Zip.
- Located the downloaded Kali Linux archive.
- Used 7-Zip to extract the archive.
- Identified the extracted virtual machine files.

*Lesson Learned:* Understanding archive formats and extraction processes is important when working with virtual machine images.

### 3. Oracle VirtualBox Installation

*Problem:*
I encountered installation issues, including a notification indicating that another installation was already running.

*Troubleshooting:*
- Checked for other active installation processes.
- Allowed the existing installation process to finish before proceeding.

*Lesson Learned:* Installation processes sometimes need to finish before another installation can begin.

### 4. VirtualBox Extension Pack

*Problem:*
I struggled to open the VirtualBox Extension Pack because Windows did not recognise the downloaded file as an application.

*Troubleshooting:*
- Identified that the Extension Pack was not a normal Windows application.
- Learned that it needed to be installed through Oracle VirtualBox.
- Explored the VirtualBox Extension Pack installation process.

### 5. Kali Linux Network Connectivity

*Problem:*
After setting up Kali Linux, I encountered network connectivity issues. The network connection appeared disconnected, preventing normal connectivity.

*Troubleshooting:*
- Checked the network connection status.
- Investigated network configuration using terminal commands.
- Explored NetworkManager and nmcli commands.
- Investigated connection errors on newer Kali Linux versions.

*Learning Outcome:* Gained exposure to Linux network management and the importance of understanding network interfaces and connection profiles.

### 6. Linux Terminal Errors

*Problem:*
While following installation and configuration instructions, I encountered terminal errors when executing certain network commands.

*Troubleshooting:*
- Reviewed the commands provided in the instructions.
- Compared the commands with the Kali Linux version being used.
- Investigated possible differences in network management configurations.

*Lesson Learned:* Commands and configurations may differ between Linux versions. It is important to understand what a command does rather than simply copying and pasting instructions.

## 📚 Skills Developed

Through this project, I am developing practical skills in:

- Linux fundamentals.
- Kali Linux installation and configuration.
- Virtual machine management.
- Oracle VirtualBox.
- Network troubleshooting.
- Linux terminal commands.
- Problem-solving and technical research.
- Technical documentation using GitHub.

## 🎯 Project Goals

My objectives for this cybersecurity lab are to:

1. Develop confidence using Linux environments.
2. Understand networking fundamentals.
3. Practise cybersecurity tools and techniques.
4. Gain hands-on experience through practical exercises.
5. Document my progress and technical discoveries.
6. Build a foundation for a career in cybersecurity.

## 💡 Key Takeaway

One of the biggest lessons from this project is that learning cybersecurity is not always about getting everything right the first time.

Sometimes it involves encountering errors, researching solutions, testing different approaches, and learning from mistakes.

Every challenge has been an opportunity to understand technology better and develop my technical problem-solving skills.

*This is the beginning of my cybersecurity journey. More labs, challenges, and projects coming soon!*

---

Documenting my learning journey, one challenge at a time. 🔐
