# Lab-05: DHCP & IP Configuration

## Objective
This lab demonstrates how to configure IP addressing and simulate DHCP behavior on Windows using Loopback Adapters. The goal is to understand static IP configuration, client IP assignment, and IP conflict simulation in a safe, isolated environment.

---

## Tools Used
- Windows OS  
- Loopback Adapter  
- Command Prompt (`ipconfig`)  

---

## Lab Steps

### Step 01: Install Loopback Adapter (Server)
- Add a Microsoft Loopback Adapter to act as the network server.  
- Screenshot: `step-01-loopback-installed.png`

### Step 02: Configure Static IP on Server (Before OK)
- Open IPv4 Properties of the Server Adapter.  
- Select **Use the following IP address** and enter:
  - IP address: `10.0.0.1`  
  - Subnet mask: `255.255.255.0`  
- Screenshot: `step-02-ip-config-before.png`

### Step 03: Verify Server IP (`ipconfig`)
- After applying settings, open Command Prompt and run:
```bash
ipconfig
