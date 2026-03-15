# Homelab Roadmap

This document outlines the current state and future development plan for my homelab infrastructure.

---

## Current State

The physical infrastructure has been assembled but is not yet fully integrated into the home network.

Completed so far:

- 12U wall-mounted rack installed
- Patch panel and structured cabling connected
- Network switch installed
- Router installed
- NAS (Synology RS1221+) installed
- UPS power protection installed
- Power distribution connected
- Rack layout documented
- Infrastructure diagrams created
- Homelab documentation repository created on GitHub

At this stage the rack is powered and assembled, but the network infrastructure is not yet fully in production.

The home network is currently still running on the existing Orbi WiFi system.

---

## Phase 1 — Network Integration

Safely introduce the new network infrastructure without disrupting the existing home network.

Planned steps:

1. Connect the current Orbi router through the new network switch  
2. Maintain the existing home network while the new infrastructure is being prepared  
3. Verify connectivity and switching behavior  

Goal:  
Introduce the rack infrastructure without affecting the household network.

---

## Phase 2 — Wireless Infrastructure

Deploy the new wireless infrastructure.

Planned:

- Install two WiFi access points
- One AP per floor
- Connect both APs through PoE
- Validate signal coverage and roaming

Goal:  
Replace the consumer mesh WiFi system with a managed network infrastructure.

---

## Phase 3 — Network Segmentation

Introduce network segmentation using VLANs.

Planned VLAN structure:

- Main network (trusted devices)
- IoT network
- Infrastructure network
- Guest network
- Lab network

Steps:

- Create VLANs on the router
- Configure switch VLAN tagging
- Assign SSIDs to VLANs
- Move devices to their proper network segment

Goal:  
Improve security and network organization.

---

## Phase 4 — Migration Off Orbi

Once the new infrastructure is stable:

- Remove Orbi from the network
- All WiFi handled by the new access points
- Router + switch handle routing and segmentation

Goal:  
Full transition to managed network infrastructure.

---

## Phase 5 — NAS and Storage Infrastructure

Improve storage infrastructure.

Planned improvements:

- Add additional drives to NAS
- Configure RAID expansion
- Implement snapshot strategy
- Configure backup workflows
- Test restore procedures

Future consideration:

- 10GbE connectivity for NAS

---

## Phase 6 — Lab Environment

Introduce compute resources for experimentation.

Planned:

- Deploy mini servers (cluster nodes)
- Install virtualization platform
- Create isolated lab environments
- Run infrastructure experiments

Possible technologies:

- Proxmox
- Docker
- containerized services

Goal:  
Build a flexible environment for infrastructure experimentation.

---

## Phase 7 — Monitoring and Observability

Add infrastructure monitoring.

Possible stack:

- Prometheus
- Grafana
- system metrics monitoring
- network traffic visibility

Goal:  
Gain operational insight into the infrastructure.

---

## Phase 8 — Backup and Disaster Recovery

Design and test recovery procedures.

Planned:

- NAS backup verification
- configuration backups
- recovery testing

Goal:  
Ensure infrastructure resilience.

---

## Long-Term Vision

The homelab serves as:

- a learning environment for networking and infrastructure
- a platform for infrastructure experimentation
- a documented engineering project
- a public portfolio demonstrating practical IT skills