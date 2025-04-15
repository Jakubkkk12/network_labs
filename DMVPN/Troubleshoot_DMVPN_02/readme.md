# 📡 Troubleshoot DMVPN 01

## 🖼️ Topology

Below is the high-level topology used in this lab:

![MPLS-TE Lab Topology](topology.png)

## 🛠️ Lab Configuration Overview

- **Technology Stack:**
  - IPv4overIPv4 DMVPN Phase 3 (GRE over IPSec with IKEv2)
  - Overlay Tunnel Network: `10.0.0.0/24`
  - Named EIGRP (AS 100) for dynamic routing
- **Key Devices:**
  - HQ (Hub)
  - BR1, BR2, BR3 (Spokes)
  - ISP (Transit/Internet Simulation)
  - PC1–PC4 (End devices connected to each branch)

## 🎯 Task

Problems:
Users from BR1 and BR2 are not able to access resources outside their brunch

Troubleshooting TASKs:
All users should have full conectivity to each others 
