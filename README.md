# Home Network Security Lab

A hands-on cybersecurity lab built to practice firewall configuration, network traffic analysis, and intrusion detection. This project simulates a small network environment where I set up and configured multiple security tools to monitor and protect a virtual network — practical experience with tools used daily by SOC analysts and network security engineers.

**Environment:** 
- pfSense VM 
- Sensor VM

---

## Lab Architecture

My network has two VMs. The **pfSense VM** sits between the internet and my LAN, acting as the firewall. The **Sensor VM** connects to that LAN and runs **Wireshark** (to capture traffic) and **Snort** (to detect suspicious traffic).

```
Internet
   │
pfSense (firewall/gateway)
   │
LAN
   │
Sensor VM → runs Wireshark + Snort
```

---

## 📂 Components

| Component | Status | Description |
|---|---|---|
| [pfSense](./pfsense) | ✅ Complete | Firewall/gateway setup, WAN/LAN config, custom rules |
| [Wireshark](./wireshark) | ✅ Complete | Packet capture and traffic analysis on the LAN |
| [Snort](./snort) | ✅ Complete | IDS setup and custom detection rules |



---

## Skills Demonstrated

`Network segmentation` `Firewall rule writing` `DHCP/static IP configuration` `Packet-level traffic analysis` `IDS configuration & custom rules` `Log analysis` `Linux fundamentals` `VirtualBox networking`

## Tools & Technologies

`VirtualBox` `pfSense` `Wireshark` `Snort` `Networking (TCP/IP, DHCP)` `Linux`

## What's Next

- Build a vulnerability scanner to round out the defensive story with an assessment component
- Add a SIEM (e.g., Security Onion or ELK stack) to centralize logs from Snort and pfSense
- Simulate a real attack scenario (e.g., using Kali Linux) to test detection end-to-end

---
