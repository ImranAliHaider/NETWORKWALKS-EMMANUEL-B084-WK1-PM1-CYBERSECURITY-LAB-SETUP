# Cybersecurity Lab Setup Using VirtualBox and Kali Linux

##  Project Introduction

In this project I created a basic cybersecurity lab using Oracle VirtualBox and Kali Linux. The main purpose was to learn how to install the required software, set up a virtual machine, and configure its network.

This is my first step toward learning cybersecurity and penetration testing in a safe environment.

##  Project Goals

- Install 7-Zip and VirtualBox.
- Download and set up Kali Linux.
- Configure the network in VirtualBox.
- Check the internet connection in Kali Linux.
- Create a snapshot to save the current VM state.
- Take screenshots of the setup process.

## Tools Used

| Tool | Purpose |
|---|---|
| 7-Zip | To extract the downloaded files |
| Oracle VirtualBox | To run a virtual machine |
| Kali Linux | To learn Linux and cybersecurity |
| Windows 10 | My main operating system |

##  Installation and Setup

### Step 1: Install 7-Zip

First, I downloaded and installed 7-Zip on my Windows computer. I used it to extract the Kali Linux files.

### Step 2: Install VirtualBox

After installing 7-Zip, I downloaded Oracle VirtualBox and installed it on my computer. VirtualBox allows me to run another operating system without replacing Windows.


<!-- Add your VirtualBox screenshot here -->
![VirtualBox Installation](01-VirtualBox-installation.png)

### Step 3: Download Kali Linux

Next, I downloaded the Kali Linux virtual machine package from the official website. I extracted the files when required and opened the virtual machine in VirtualBox.

**Download:** https://www.kali.org/get-kali/

**Screenshot:**
<!-- Add your Kali Linux download or import screenshot here -->
![Kali Linux Setup](screenshots/03-kali-linux-setup.png)

### Step 4: Configure the Virtual Machine

I checked the virtual machine settings before starting Kali Linux. I assigned memory to the VM and selected the appropriate network option in VirtualBox.

The settings used on my computer should be documented with screenshots.

**Screenshot:**
<!-- Add your VM settings screenshot here -->
![Virtual Machine Settings](screenshots/04-vm-settings.png)

### Step 5: Configure the Network

After starting Kali Linux, I checked the network connection and IP address. I also learned how the IP address, gateway, and DNS help a computer communicate with other devices and access the internet.

Commands used to check the network:

```bash
ip a
ip route
ping -c 4 8.8.8.8
```

These commands help me check the network interfaces, default route, and internet connectivity. The results may differ depending on the network configuration.

**Screenshot:**
<!-- Add your actual terminal screenshot here -->
![Network Configuration](screenshots/05-network-configuration.png)

### Step 6: Create a Snapshot

After completing the initial setup, I created a snapshot of the virtual machine. A snapshot saves the VM's current state so I can return to it if something goes wrong during future practice.

**Screenshot:**
<!-- Add your snapshot screenshot here -->
![Kali Linux Snapshot](screenshots/06-kali-snapshot.png)

## ✅ Testing

I used basic commands to check whether Kali Linux was working correctly.

| Command | Purpose |
|---|---|
| `ip a` | Check the IP address |
| `ip route` | Check the network route |
| `ping -c 4 8.8.8.8` | Test internet connectivity |
| `nmap --version` | Check whether Nmap is installed |

**Note:** I will add my actual results and screenshots after running these commands.

## 📚 What I Learned

During this project, I learned:

- How to install software on Windows.
- How to use VirtualBox.
- How to set up Kali Linux as a virtual machine.
- How to check IP addresses and network connectivity.
- How to create a VM snapshot.
- How to save screenshots and document my work.

## 🔒 Safe Use

I will use this lab for learning and practice only. I will perform security testing only on my own systems or on systems for which I have permission.

## 🚀 Future Plans

In the future, I plan to:

- Learn more Kali Linux commands.
- Practice basic networking.
- Learn how to use Nmap.
- Add another virtual machine for testing.
- Explore basic cybersecurity tools.

## 👨‍🎓 About This Project

**Project:** Cybersecurity Lab Setup  
**Program:** Cybersecurity Internship  
**Week:** 01  
**Level:** Beginner

This project helped me understand the basic steps required to create a virtual lab for cybersecurity learning.

