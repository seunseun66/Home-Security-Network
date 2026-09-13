# Wireshark Traffic Analysis

**Plan:** Capture and analyze live network traffic passing through the lab.

## Steps
1. Used tshark (CLI) on the Sensor VM to capture traffic on port 23.
2. Filtered for Telnet traffic to verify the pfSense firewall rule was actually blocking it.
3. Every attempt to connect on port 23 failed to get a response, confirming the Telnet block was working.

## Skills Demonstrated
- Packet-level traffic analysis
- Command-line packet capture (tshark)
- Verifying firewall behavior at the network level

## Screenshots
<img width="951" height="805" alt="Screenshot 2026-09-12 223657" src="https://github.com/user-attachments/assets/da469af4-416e-4426-b71c-9526149b6755" />
