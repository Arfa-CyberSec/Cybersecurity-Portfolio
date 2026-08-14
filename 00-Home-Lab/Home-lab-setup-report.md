# Home Lab Setup Report

**30-Day Cybersecurity Bootcamp — Day 1**

---

## 1. Objective

The purpose of this home laboratory is to provide a controlled environment for hands-on cybersecurity learning throughout my 30-day cybersecurity bootcamp.

The laboratory will be used to develop practical skills in Linux, networking, network traffic analysis, security monitoring, digital forensics, incident response, CTF challenges, and other authorized cybersecurity exercises.

The environment is designed to allow practical experimentation within virtual machines and other controlled learning environments.

---

## 2. Lab Environment

| Component | Details |
|---|---|
| Host Operating System | Windows |
| Virtualization Platform | Oracle VM VirtualBox |
| Security Operating System | Kali Linux |
| Kali Linux Version | 2026.2 |
| Architecture | x86_64 |
| Linux Kernel | 6.19.14+kali-amd64 |
| Allocated VM Memory | 2048 MB |
| Virtual Disk | 20 GB |
| Hostname | KALI |
| Primary Network Interface | eth0 |
| VirtualBox Network Mode | NAT |
| Lab Status | Operational |

---

## 3. Virtualization Environment

Kali Linux is configured as a virtual machine using Oracle VM VirtualBox.

The VirtualBox environment also contains a Metasploitable virtual machine. At the time of documentation, the Metasploitable machine is powered off. It will be used only in later controlled and authorized security-testing exercises when required.

### Figure 1 — VirtualBox Laboratory Environment

**[INSERT SCREENSHOT HERE: `virtualbox-kali-lab.png`]**

*Figure 1. Kali Linux virtual machine running in Oracle VM VirtualBox. The VirtualBox environment also contains a Metasploitable virtual machine for future controlled laboratory exercises.*

---

## 4. Kali Linux Environment

Kali Linux is being used as the primary security-focused operating system for the bootcamp.

The installed environment is Kali GNU/Linux Rolling, version 2026.2, running on an x86_64 architecture with the 6.19.14+kali-amd64 Linux kernel.

The Kali virtual machine has 2048 MB of allocated memory and a 20 GB virtual disk.

### Figure 2 — Kali Linux System Environment

**[INSERT SCREENSHOT HERE: `kali-system-verification.png`]**

*Figure 2. Kali Linux desktop and terminal environment showing system and operating-system verification.*

---

## 5. System Verification

The following commands were used to verify the operating system, system identity, network configuration, and available system resources:

```bash
whoami
hostname
uname -a
cat /etc/os-release
ip addr
ip route
free -h
```
Verification Results

* whoami verified the active Linux user account.
* hostname verified the system hostname as KALI.
* uname -a verified the Linux kernel version and system architecture.
* cat /etc/os-release confirmed Kali GNU/Linux Rolling, version 2026.2.
* ip addr was used to identify the active network interface and its configuration.
* ip route was used to identify the default route and routing configuration.
* free -h was used to verify the memory available to the Kali virtual machine.

For public portfolio documentation, personal account information, MAC addresses, and exact private network addresses have been redacted from screenshots where applicable.

---

## 6. Network Configuration

The Kali Linux virtual machine is configured to use Oracle VM VirtualBox's NAT (Network Address Translation) networking mode.

Within Kali Linux, the primary network interface is eth0, which is active and configured with a private IPv4 address.

The routing table shows that network traffic is routed through the virtual machine's NAT gateway.

NAT provides the virtual machine with network connectivity while keeping the laboratory environment separated from directly participating in the host's physical local network.

The exact private IP address, gateway address, and MAC address are intentionally omitted from the public portfolio because they are not necessary for demonstrating the technical objective of this setup.

---

## 7. Security Boundaries

This laboratory is intended exclusively for authorized cybersecurity education and experimentation.

Activities within the laboratory will be limited to:

* Systems and virtual machines owned or controlled by me
* Intentionally vulnerable laboratory environments
* Authorized CTF platforms
* Provided datasets and packet captures
* Educational security exercises
* Systems for which explicit permission has been obtained

Testing against third-party systems or networks without authorization will not be performed.

---

## 8. Lab Readiness

The laboratory is currently operational and ready to support the cybersecurity bootcamp.

The environment will initially support:

1. Linux command-line exercises
2. Linux filesystem and permissions practice
3. CTF challenges
4. Networking fundamentals
5. Network traffic analysis
6. Wireshark investigations
7. Security monitoring
8. Windows investigation
9. Incident-response exercises

The existing Metasploitable virtual machine provides an additional controlled environment that can be incorporated into later security-testing exercises.

---

## 9. Evidence Collected

The following evidence was collected during the initial laboratory verification:

1. Oracle VM VirtualBox screenshot showing the Kali Linux virtual machine running.
2. Kali Linux desktop and terminal screenshot showing system information.
3. Operating-system and kernel verification through Linux commands.
4. Network interface and routing verification.
5. Virtual machine hardware configuration.
6. Verification of the VirtualBox NAT network configuration.

---

## 10. Lab Status

Status: Operational

Bootcamp Progress: Day 1 / 30

The cybersecurity laboratory has been successfully verified and documented.

---

## 11. Next Step

The next stage of the bootcamp will focus on Linux fundamentals, including:

* Filesystem navigation
* File and directory management
* File permissions
* Process management
* Searching and filtering
* Basic command-line investigation

Next milestone: Day 2 — Linux Foundations

---
