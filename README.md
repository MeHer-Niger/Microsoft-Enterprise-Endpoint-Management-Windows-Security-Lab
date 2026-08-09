# Microsoft Enterprise Endpoint Management & Windows Security Lab

A hands-on enterprise IT support lab focused on Windows endpoint administration, Microsoft device management, endpoint security, networking, troubleshooting, and technical documentation.

The project simulates common tasks performed by IT Support, Service Desk, Desktop Support, and Endpoint Management professionals in a Microsoft-based enterprise environment.

---

## Project Overview

The purpose of this project is to build practical experience in supporting, configuring, troubleshooting, and securing Windows endpoints.

The lab covers areas such as:

- Windows workstation configuration
- Microsoft Intune fundamentals
- User and device management
- Windows security
- BitLocker
- Windows Update
- Network configuration
- DNS and internet connectivity troubleshooting
- Command-line troubleshooting
- IT support documentation

The project follows a structured support process:

**Identify → Investigate → Troubleshoot → Resolve → Test → Document**

---

## Project Objectives

The main objectives of this project are to:

- Build practical Windows endpoint support skills
- Understand Microsoft enterprise device-management concepts
- Practice endpoint security configuration
- Develop systematic troubleshooting skills
- Understand common networking and connectivity problems
- Practice user and device administration
- Improve technical documentation skills
- Build experience relevant to enterprise IT support environments

---

## Technologies & Tools

### Microsoft & Windows

- Windows 10/11
- Microsoft Intune
- Microsoft 365 fundamentals
- Windows Security
- BitLocker
- Windows Update
- Windows Firewall
- Windows Administrative Tools

### Networking

- TCP/IP
- DNS
- DHCP fundamentals
- IP addressing
- Network adapters
- Windows networking tools

### Troubleshooting Tools

- Command Prompt
- PowerShell
- `ping`
- `ipconfig`
- `nslookup`
- Windows Event Viewer
- Device Manager
- Windows Services
- Windows Settings

### Virtualization

- VMware
- Windows Virtual Machines

### Documentation

- GitHub
- Screenshots
- Step-by-step troubleshooting notes
- Technical reports

---

# Lab Environment

The project uses virtual Windows workstations to simulate an enterprise IT support environment.

Typical lab components include:

```text
Microsoft / Enterprise Services
            |
            |
      Windows Endpoint
            |
     -----------------
     |       |       |
 Security  Network  Users
     |       |       |
 BitLocker  DNS   Accounts
 Firewall   TCP/IP Devices
 Updates    DHCP   Access
```

Virtualization allows configurations and troubleshooting scenarios to be tested without affecting a production computer.

---

# Project Areas

## 1. Windows Endpoint Setup

Windows workstations are installed and configured for enterprise IT support practice.

Tasks include:

- Windows installation and configuration
- Computer settings configuration
- Local user configuration
- Software installation
- Windows Update configuration
- Network configuration
- Device and peripheral setup

---

## 2. Microsoft Intune & Endpoint Management

This section focuses on Microsoft endpoint-management concepts and practical Intune fundamentals.

Areas practiced include:

- Device-management concepts
- Windows endpoint administration
- User and device management
- Device configuration
- Security settings
- Endpoint policy concepts
- Compliance concepts

> This project focuses on building practical foundational knowledge of Microsoft Intune and enterprise endpoint management.

---

## 3. Windows Security

Windows endpoints are configured using common security features.

Security areas include:

- Windows Security
- Microsoft Defender fundamentals
- Windows Firewall
- Windows Update
- User access
- Device security
- Endpoint security configuration

---

## 4. BitLocker Drive Encryption

BitLocker is used to practice Windows device encryption and endpoint protection.

Tasks include:

- Enabling BitLocker
- Reviewing encryption settings
- Understanding recovery keys
- Checking encryption status
- Understanding the role of disk encryption in enterprise security

---

## 5. User & Access Management

The lab includes basic user and access-management exercises.

Topics include:

- User accounts
- Local users
- User permissions
- Device access
- Identity-management fundamentals
- User and device-management concepts

---

## 6. Network Configuration

Windows network configuration is practiced using both graphical and command-line tools.

Topics include:

- IP addressing
- Network adapters
- TCP/IP
- DNS
- DHCP fundamentals
- Default gateway
- Network connectivity

---

# Network Troubleshooting

One of the major areas of the project is troubleshooting Windows network and internet connectivity problems.

A typical troubleshooting workflow is:

```text
User reports no internet
        |
        v
Check network adapter
        |
        v
Check IP configuration
        |
        v
Test local connectivity
        |
        v
Test default gateway
        |
        v
Test external IP address
        |
        v
Test DNS resolution
        |
        v
Identify the cause
        |
        v
Apply solution
        |
        v
Test connectivity
        |
        v
Document resolution
```

---

## Example Troubleshooting Commands

### Check network configuration

```cmd
ipconfig /all
```

### Test connectivity

```cmd
ping 8.8.8.8
```

### Test DNS resolution

```cmd
ping google.com
```

### Query DNS

```cmd
nslookup google.com
```

### Refresh the IP configuration

```cmd
ipconfig /release
ipconfig /renew
```

### Clear DNS cache

```cmd
ipconfig /flushdns
```

These commands help determine whether a connectivity problem is related to:

- Network configuration
- IP addressing
- Default gateway
- DNS
- Network adapter
- Internet connection

---

# Troubles
