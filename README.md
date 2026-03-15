# Home Infrastructure Lab

Real hardware infrastructure lab used for networking, Linux, and infrastructure engineering experiments.

---

This repository documents the design, build, and evolution of a personal home infrastructure lab focused on networking, Linux systems, and infrastructure engineering.

The lab is used to experiment with real infrastructure hardware, networking architecture, and system administration in a controlled environment.

---

# Goals

- Learn Linux system administration
- Practice networking and infrastructure concepts
- Build and maintain a small home datacenter
- Experiment with virtualization and container workloads
- Document infrastructure design and troubleshooting

---

# Current Infrastructure

## Network

- UniFi Dream Machine Pro Max (router / firewall)
- UniFi Switch
- Structured CAT6 Ethernet cabling
- Patch panel

## Storage

- Synology RS1221+
- RAID storage for backups and lab services

## Power

- APC Rack UPS for power protection

## Workstations

- Falcon Talon workstation  
  Ryzen 7 • RTX 5090 • 96GB RAM • 16TB NVMe

- Mac Studio M1 Max  
  Used for development and documentation

---

# Lab Architecture

The lab is built around a wall-mounted network rack with structured cabling and dedicated infrastructure hardware.

## Rack Layout

Diagram showing the physical layout of the rack including:

- patch panel
- PoE switch
- gateway
- NAS
- UPS power system

[View rack layout diagram](rack-diagram.png)

---

# Infrastructure Stack

## Networking

- UniFi Dream Machine Pro Max
- UniFi Switch
- Structured Ethernet cabling

## Storage

- Synology RS1221+
- RAID storage

## Power

- APC rack UPS

## Compute

- Falcon Talon workstation
- Mac Studio M1 Max

---

# Future Lab Expansion

Planned infrastructure improvements:

- Dell OptiPlex micro nodes
- Linux virtualization cluster
- container workloads
- infrastructure monitoring
- logging and observability

---

# Documentation

Additional documentation:

- [Rack Layout](docs/rack-layout.md)
- [Network Infrastructure](docs/network.md)
- [Infrastructure Services](docs/services.md)

---

# Learning Focus

Current learning areas:

- Linux administration
- networking fundamentals
- infrastructure architecture
- virtualization
- containerization

---

# Rack Build Progress

## Rack Installation

Initial installation of the wall-mounted rack and infrastructure components.

![Rack Installation](photos/rack-installation-start.webp)

## Network Stack Deployment

Installation of networking equipment.

![Network Stack](photos/network-stack-install.webp)

## Final Rack Layout

Completed rack configuration.

![Rack Layout](photos/rack-final-layout.webp)

---

# Engineering Journal

Detailed experiments and troubleshooting notes are documented on the website:

https://eugeneivanov.dev

---

# Author

Eugene Ivanov  
Infrastructure Engineering  

Austin, Texas

LinkedIn  
https://www.linkedin.com/in/eugeneivanov-dev

Website  
https://eugeneivanov.dev