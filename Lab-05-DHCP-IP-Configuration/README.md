# Lab-05: DHCP & IP Configuration

## Objective
Configure IP addressing and simulate DHCP using Loopback Adapters on Windows.

## Steps

1. **Install Loopback Adapter (Server)**  
   - Screenshot: `step-01-loopback-installed.png`

2. **Set Static IP on Server (10.0.0.1 / 255.255.255.0)**  
   - Screenshot: `step-02-ip-config-before.png`

3. **Verify Server IP with ipconfig**  
   - Screenshot: `step-03-ipconfig-result.png`

4. **Install Loopback Adapter (Client)**  
   - Screenshot: `step-04-loopback-client-installed.png`

5. **Client on Obtain IP automatically**  
   - Screenshot: `step-05-client-ip-auto.png`

6. **Assign Static IP to Client (10.0.0.2 / 255.255.255.0) + ipconfig**  
   - Screenshot: `step-06-client-ip-assigned.png`

7. **Prepare Client for IP Conflict Simulation**  
   - Screenshot: `step-07-client-ip-conflict.png`

## Notes
- Lab executed locally using Loopback Adapters.  
- Demonstrates IP configuration and conflict handling without affecting real network.  - IP address: `10.0.0.1`  
  - Subnet mask: `255.255.255.0`  
- Screenshot: `step-02-ip-config-before.png`

### Step 03: Verify Server IP (`ipconfig`)
- After applying settings, open Command Prompt and run:
```bash
ipconfig
