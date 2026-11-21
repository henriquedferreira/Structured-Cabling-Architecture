# Structured Cabling Architecture — Multi-Building Campus LAN

End-to-end physical and logical network infrastructure plan designed for a four-building educational campus (Dr. Joaquim Gomes Ferreira Alves Secondary School), developed for the **Structured Cabling** course at **ISEC** (Coimbra Institute of Engineering).

## Project Scope & Compliance

This project delivers a scalable, converged LAN architecture designed to modernize legacy campus connectivity across three academic pavilions and a central services building. The physical layer and documentation strictly adhere to **ISO/IEC 11801** (hierarchical star topology) and **ANSI/TIA-606-C** (standardized port/rack labeling), validated through logical modeling and wireless coverage mapping in **Cisco Packet Tracer**.

## Physical Layer & Cabling Topology

* **Campus & Vertical Backbone:** Multimode **OM4 optical fiber** interconnecting the central Campus Distributor (MDF) in Pavilion B to Building Distributors (BDFs) and floor-level Intermediate Distribution Frames (IDFs), ensuring 10G/40G readiness and EMI immunity.
* **Horizontal Distribution:** Full **Category 6A (Cat6A)** copper cabling from IDFs to Telecommunications Outlets (TOs), supporting 10GBASE-T speeds up to 100 meters for high-density classrooms and Wi-Fi access points.
* **Structured Administration:** Standardized physical identification scheme (`DE-DP.PP-XX`) compliant with ANSI/TIA-606-C across all patch panels, racks, and endpoints to streamline long-term maintenance.

## Logical Design & Converged Services

* **Traffic Segmentation:** VLAN-based logical isolation separating Student, Faculty, Administrative, and Guest networks to enforce security policies and broadcast control.
* **Triple-Play Convergence:** Unified infrastructure supporting high-speed data, VoIP telephony, centralized authentication, and campus-wide managed Wi-Fi coverage.
* **Enterprise Hardware & Resilience:** Complete active/passive Bill of Materials (BOM) featuring next-gen firewalls (FortiGate), PoE+ managed switching, centralized WLAN controllers, redundant UPS power protection, and full deployment budgeting.
