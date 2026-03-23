# Lab-06: Wi-Fi Troubleshooting

## Objective
Simulate and troubleshoot Wi-Fi connectivity issues on Windows by modifying IP configuration settings.

## Steps

### 1. Verify Wi-Fi Connection
- Checked network status using `ipconfig`
- Confirmed valid IP address, gateway, and DNS
- Screenshot: `step-01-wifi-connected.png`

### 2. Simulate IP Misconfiguration
- Manually configured incorrect static IP settings
- Result: Internet connectivity lost
- Screenshot: `step-02-wrong-ip-config.png`

### 3. Test Connectivity Issue
- Used `ping 8.8.8.8` to test network access
- Result: Request failed due to incorrect IP configuration
- Screenshot: `step-03-ping-failed.png`

### 4. Fix IP Configuration
- Reverted settings to:
  - Obtain IP address automatically
  - Obtain DNS automatically
- Screenshot: `step-04-ip-fixed.png`

### 5. Verify Connectivity Restored
- Retested using `ping 8.8.8.8`
- Result: Successful replies received
- Screenshot: `step-05-ping-success.png`

## Notes
- Lab performed on a real Wi-Fi network
- Demonstrates DHCP-related issues and troubleshooting steps
- No permanent changes were made to the system
