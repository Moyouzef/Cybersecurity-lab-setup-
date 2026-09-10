# Cybersecurity-lab-setup-
Cybersecurity Project Week 1
**Penetration Testing Lab Environment**


**1. Overview**

This repository documents the setup and configuration of my personal penetration testing laboratory. The lab was created using Oracle VirtualBox with Kali Linux as the primary penetration testing environment.

The purpose of this lab is to develop practical cybersecurity and penetration testing skills in a controlled and isolated environment. It will be used for authorized security testing, network reconnaissance, vulnerability assessment, and other cybersecurity exercises.


I installed Oracle VirtualBox as the virtualization platform for creating and managing the cybersecurity laboratory.

VirtualBox allows me to run Kali Linux and other virtual machines independently from my main operating system.

**Step 2 — Download and Install Kali Linux**

I installed Kali Linux as the main penetration testing operating system.

Kali Linux was selected because it is specifically designed for security testing and includes many pre-installed cybersecurity and penetration testing tools.

After installation, I started Kali Linux successfully inside VirtualBox.

**Step 3 — Configure the Virtual Machine**

After installing Kali Linux, I reviewed the VirtualBox virtual machine configuration.



I checked:

CPU allocation

RAM allocation

Storage

Network adapter

Boot configuration

Virtual machine connectivity

The purpose was to ensure that Kali Linux had sufficient resources and an appropriate network configuration for the lab.

**Step 4 — Configure the Network**

I checked the network settings in VirtualBox and Kali Linux.

The VirtualBox network adapter was configured according to the requirements of the laboratory environment.

I also checked the network configuration inside Kali Linux to verify that the virtual machine received the expected IP address and network information.

**Step 5 — Challenges Faced**

During the lab setup, I faced a network configuration issue in Kali Linux. While testing the network interface, I ran the following command:

sudo ifconfig eth0 down

After disabling the eth0 interface, I was unable to bring it back up normally. I investigated the issue and checked the relevant system configuration files. I made the necessary changes to the network configuration and restarted the virtual machine.

After restarting the machine, the network interface was working correctly again.

This challenge helped me improve my understanding of Linux network interfaces and gave me practical experience troubleshooting network configuration issues in a virtualized penetration-testing lab environment.

**Learning and Guidance**

I developed and configured this penetration testing laboratory as part of my practical cybersecurity learning under the guidance of my tutor, **Waqas Kareem.**
