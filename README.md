# Week-2-IP-Addressing-FLSM-VLSM-and-VLAN-Configuration


## 📌 Overview

This repository contains my Week 2 internship submission, focused on strengthening core networking fundamentals: IP addressing and network segmentation.

The task covers two major areas:

1. **Subnetting** – Fixed Length Subnet Masking (FLSM) and Variable Length Subnet Masking (VLSM), including calculation of network addresses, subnet masks, broadcast addresses, and usable host ranges.
2. **VLANs** – Configuring, assigning, and verifying Virtual Local Area Networks on Cisco switches using Cisco Packet Tracer and GNS3, including access ports, trunk links, and connectivity verification.

---

## 🎯 Objectives

- Understand the concepts and importance of FLSM in network design.
- Learn VLSM to efficiently allocate IP addresses based on differing host requirements.
- Calculate network addresses, subnet masks, broadcast addresses, and usable host ranges for FLSM and VLSM scenarios.
- Understand the concept, purpose, and advantages of VLANs.
- Configure and verify VLANs on switches using Cisco Packet Tracer and GNS3.

---

## 🛠 Tools Used

- **Cisco Packet Tracer**
- **GNS3**
- **PuTTY**

---

## 📂 Repository Structure

```
Week2/
├── Report.pdf                  # Weekly report: objectives, steps, screenshots, challenges, outcomes
├── FLSM_Worksheet.pdf          # 10+ FLSM subnetting problems with detailed calculations
├── VLSM_Worksheet.pdf          # 5+ VLSM design scenarios with IP allocation
├── IP_Addressing_Report.pdf    # Explanation of FLSM, VLSM, and subnet calculations
├── Cisco_Packet_Tracer.pkt     # VLAN topology: access ports, trunk ports, verification
├── GNS3_Project/                # VLAN topology recreated in GNS3
├── Screenshots/                 # Verification evidence (see below)
├── Topology_Diagram.png         # Labeled network diagram (switches, PCs, VLAN IDs, IPs)
└── README.md
```

---

## 📋 Deliverables

- [x] FLSM Worksheet — 10 subnetting problems solved with full calculations
- [x] VLSM Worksheet — 5 VLSM design scenarios with proper IP allocation
- [x] IP Addressing Report (PDF)
- [x] Cisco Packet Tracer project (.pkt) — working VLAN topology
- [x] GNS3 project — VLAN topology recreated and verified
- [x] Verification screenshots
- [x] Labeled network topology diagram
- [x] Weekly report (PDF)

---

## ✅ Verification Commands

Connectivity and configuration were verified using standard Cisco IOS commands:

```
show vlan brief
show interfaces trunk
ping <destination-ip>
```

Screenshots of the output from these commands are included in the `Screenshots/` folder as evidence of successful VLAN configuration and inter-VLAN connectivity (where applicable).

---

## 📈 Learning Outcomes

By completing this task, the following skills were developed:

- Explaining the differences between FLSM and VLSM
- Calculating network addresses, subnet masks, broadcast addresses, and host ranges
- Designing efficient, scalable IP addressing schemes for enterprise networks
- Configuring and verifying VLANs, access ports, and trunk ports on Cisco switches
- Applying network segmentation for improved security, performance, and manageability
- Producing professional network documentation (diagrams, configs, and reports)

---

## 🔗 Submission Links

- **LinkedIn Post:** [Add link here]

---

## 🏢 Company Information

- **Company:** IT-SIMPLERA Institute
- **Department:** Network Administration
- **Supervisor:** Senior Network Administrator (Jawad Qayum)

