# Network Topology

## Lab Overview
This document outlines the IP addressing and connectivity for the current pentest engagement environment.

## Diagram / Layout
- **Attacker (Parrot OS):** 192.168.1.X
- **Firewall (OPNsense):** 192.168.1.1
- **Target 1 (Metasploitable 2):** 192.168.1.Y
- **Target 2 (Windows Server):** 192.168.1.Z
## Notes
- **Current State:** Flat Network (Bridged mode). 
- All machines are reachable directly from the attacker machine.
- OPNsense is currently present in the topology but not actively filtering traffic.
- Future Goal: Migrate to Host-Only/Segmented VSwitch to test OPNsense firewall rules and IDS/IPS capabilities.
