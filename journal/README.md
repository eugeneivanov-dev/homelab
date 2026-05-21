# Engineering Journal

Short notes about infrastructure work, lab experiments, and physical network setup.

---

## 2026-05-21 - Planned Enterprise Linux Administration Lab on Proxmox

Defined a new Proxmox-based enterprise Linux lab project focused on RHEL administration, Oracle Linux comparison, SELinux, firewalld, systemd services, monitoring, and storage mount practice.

More details: https://eugeneivanov.dev/projects/enterprise-linux-administration-lab-on-proxmox/

---

## 2026-05-21 — Microsoft 365 Identity and Endpoint Administration Lab

Added a project to study Microsoft 365 as an enterprise platform for identity, access, collaboration services, security basics, and endpoint management.

More details: https://eugeneivanov.dev/projects/microsoft-365-identity-and-endpoint-administration-lab/

---

## 2026-05-20 — CCNA Foundation for Infrastructure Engineering

Defined a focused project to use CCNA not as a checkbox certification, but as a structured path for building networking thinking, packet-flow understanding, and stronger infrastructure troubleshooting skills.

More details: https://eugeneivanov.dev/projects/ccna-foundation-for-infrastructure-engineering/

---

## 2026-05-20 — Building a Cross-Platform Unity Workspace for a Beginner C# Programmer

Set up a clean Windows and macOS development workflow for a beginner Unity/C# programmer using GitHub as the source of truth, a proper Unity .gitignore, and a structured first project repository.

More details: https://eugeneivanov.dev/journal/labnotes/building-cross-platform-unity-workspace-for-beginner-csharp-programmer/

---

## 2026-05-16 - Planned Windows Server 2025 Infrastructure Lab

Planned a staged Windows Server 2025 infrastructure lab on Proxmox with Active Directory, DNS, Windows 11 domain clients, Group Policy, file services, and future Domain Controller redundancy.

More details: https://eugeneivanov.dev/projects/windows-server-2025-infrastructure-lab-on-proxmox/

---

## 2026-05-16 - Wireshark Packet Analysis Workflow

Defined a practical packet capture workflow for the home lab using Wireshark, tcpdump, and UniFi port mirroring to support evidence-based network troubleshooting.

More details: https://eugeneivanov.dev/projects/wireshark-packet-analysis-workflow/

---

## 2026-05-15 — Planned NetBox Source of Truth Implementation

Defined a project to deploy NetBox as the internal source of truth for documenting network devices, VLANs, IPAM, cabling, Proxmox virtualization, services, monitoring, and backup expectations in the home infrastructure lab.

More details: https://eugeneivanov.dev/projects/netbox-source-of-truth-implementation/

---

## 2026-05-12 - Troubleshooting Noisy Grafana Memory Alerts in a Proxmox Home Lab

Investigated noisy Grafana memory alerts, confirmed the VM had no real Linux memory pressure, and replaced the Proxmox memory-percentage alert with a more accurate node_exporter MemAvailable-based rule.

More details: https://eugeneivanov.dev/journal/troubleshooting/troubleshooting-noisy-grafana-memory-alerts-proxmox/

---

## 2026-05-11 — Building a Self-Hosted Observability Stack for a Home Lab

Published a high-level overview of the self-hosted observability stack, linking the full series covering Ubuntu VM preparation, Prometheus, Grafana, Node Exporter, Blackbox Exporter, Proxmox monitoring, dashboards, and alerting.

More details: https://eugeneivanov.dev/journal/labnotes/building-self-hosted-observability-stack-for-home-lab/

---

## 2026-05-11 — Configuring Grafana Alerts and Email Notifications with Proton SMTP

Configured Grafana alert rules and Proton SMTP email notifications for HTTP service availability, Proxmox objects, Node Exporter targets, disk usage, memory usage, and controlled DOWN/UP alert validation.

More details: https://eugeneivanov.dev/journal/labnotes/configuring-grafana-alerts-and-email-notifications-with-proton-smtp/

---

## 2026-05-11 — Organizing Grafana Dashboards for Home Lab Observability

Organized the Grafana dashboard layer into focused views for Linux VM metrics, HTTP service availability, Proxmox infrastructure health, and alert visibility across the home lab monitoring stack.

More details: https://eugeneivanov.dev/journal/labnotes/organizing-grafana-dashboards-for-home-lab-observability/

---

## 2026-05-10 — Adding Proxmox Monitoring with Prometheus PVE Exporter

Integrated Proxmox into the monitoring stack with a dedicated API user and token, Prometheus PVE Exporter, pve_up validation, and Grafana panels for node, VM, storage, disk, and memory metrics.

More details: https://eugeneivanov.dev/journal/labnotes/adding-proxmox-monitoring-with-prometheus-pve-exporter/

---

## 2026-05-10 — Monitoring HTTP Service Availability with Blackbox Exporter

Added HTTP service availability monitoring with Blackbox Exporter, Prometheus probe_success checks, Grafana UP/DOWN status panels, and validation for self-hosted lab services.

More details: https://eugeneivanov.dev/journal/labnotes/monitoring-http-service-availability-with-blackbox-exporter/

---

## 2026-05-10 — Monitoring Linux VMs with Node Exporter and Prometheus

Expanded the monitoring stack from a single monitoring VM to multiple Linux VMs using Node Exporter, UFW access control, Prometheus scrape targets, readable instance labels, and Grafana validation.

More details: https://eugeneivanov.dev/journal/linux/monitoring-linux-vms-with-node-exporter-and-prometheus/

---

## 2026-05-09 — Deploying Prometheus and Grafana on an Ubuntu Monitoring VM

Deployed the initial monitoring core with Prometheus, Grafana, and Node Exporter on an Ubuntu Server VM using Docker Compose, persistent volumes, Prometheus target validation, and a working Grafana datasource.

More details: https://eugeneivanov.dev/journal/labnotes/deploying-prometheus-and-grafana-on-ubuntu-monitoring-vm/

---

## 2026-05-09 — Preparing an Ubuntu Server VM for Docker-Based Infrastructure Services

Documented a repeatable Ubuntu Server VM baseline for Docker-based infrastructure services, including system validation, Docker installation, Docker Compose checks, project directory structure, and basic operational readiness.

More details: https://eugeneivanov.dev/journal/linux/preparing-ubuntu-server-vm-for-docker-infrastructure/

---

## 2026-05-08 - Custom 404 Page with Correct Nginx Error Handling

Built a branded Hugo 404 page and configured production Nginx behavior so missing routes preserve HTTP 404 status while displaying the custom error page.

More details: https://eugeneivanov.dev/journal/troubleshooting/custom-404-page-hugo-nginx-cloudways/

---

## 2026-05-07 - Self-Hosted Matomo Analytics with Docker and Cloudflare Tunnel

Deployed Matomo on a dedicated Ubuntu VM with Docker Compose and MariaDB, exposed it through Cloudflare Tunnel, added the tracking code to the site, and configured both VM-level and database-level backups.

More details: https://eugeneivanov.dev/journal/linux/matomo-self-hosted-docker-cloudflare-tunnel/

---

## 2026-05-07 - Self-Hosted Plausible Analytics Deployment

Deployed Plausible Community Edition on Ubuntu Server using Docker Compose and Cloudflare Tunnel with realtime analytics successfully tracking live traffic.

More details: https://eugeneivanov.dev/journal/linux/plausible-self-hosted-docker-cloudflare-tunnel/

---

## 2026-05-06 — Updated Umami Analytics Stack to Version 3.1

Updated the self-hosted Umami analytics stack on Ubuntu with Docker Compose, verified database migrations, validated realtime tracking, and confirmed analytics collection across multiple devices and operating systems.

More details: https://eugeneivanov.dev/journal/linux/updating-umami-to-version-3-1/

---

## 2026-05-06 — Fixed Proxmox Enterprise Repository Update Errors

Investigated repeated apt update failures in Proxmox, identified unauthorized enterprise repositories as the root cause, migrated the node to the no-subscription repository, and restored normal package update operation.

More details:  https://eugeneivanov.dev/journal/troubleshooting/fixing-proxmox-enterprise-repository-errors/

---

## 2026-04-25 - Defining My CCNA Preparation Stack

A short lab note on how I structured my CCNA preparation around a primary path, delayed reinforcement, and practical lab work without turning the process into unnecessary duplication.

More details: https://eugeneivanov.dev/journal/labnotes/defining-my-ccna-preparation-stack/

---

## 2026-04-24 - Protecting the First Cognitive Block of the Day

A short note on why I now keep the first work block of the day for learning and move heavier operational and execution tasks later.

More details: https://eugeneivanov.dev/journal/labnotes/protecting-the-first-cognitive-block-of-the-day/

---

## 2026-04-17 - The real goal of automation

The goal is not simply moving from GUI to CLI, but moving from touching one thing at a time toward controlling the whole estate.

More details: https://eugeneivanov.dev/journal/labnotes/follow-up-that-clarified-the-real-goal-of-automation/

---

## 2026-04-16 - Rethinking VLANs, automation, and the next stage of my home lab

A useful conversation with a Senior Systems Engineer helped me sharpen how I think about VLAN boundaries, reproducible infrastructure, automation, cloud, and the right build order for the next stage of my lab.

More details: https://eugeneivanov.dev/journal/labnotes/rethinking-vlans-automation-and-home-lab/

---

## 2026-04-15 - DNS, CCNA, and a better learning loop

Returned to Google IT Support, saw the need for a dedicated DNS server in my lab, and confirmed that pairing structured study with deeper CCNA reading is the best fit for how I learn and turn new knowledge into infrastructure decisions.

More details: https://eugeneivanov.dev/journal/labnotes/from-dns-to-ccna-a-better-learning-loop/

---

## 2026-04-12 - Tailscale ACL for Minecraft Access Control

Implemented controlled remote access to a private Minecraft server using Tailscale ACLs, transitioning from open network trust to explicit, group-based access rules.

More details: https://eugeneivanov.dev/journal/networking/tailscale-acl-minecraft-access-control/

---

## 2026-04-11 - Stabilizing a Proxmox Host That Stayed Powered On but Dropped Off the Network

Documented how I diagnosed an intermittent Proxmox network hang, confirmed a temporary fix by disabling NIC offloading, and then made the solution persistent after 120 hours of stability.

More details: https://eugeneivanov.dev/journal/troubleshooting/proxmox-host-powered-on-but-offline-nic-offloading-fix/

---

## 2026-04-11 - Roadmap Expanded with Certifications and Reading

I updated my infrastructure roadmap to include a focused certification path and a core technical reading library to support deeper systems thinking and long-term architectural growth.

More details: https://eugeneivanov.dev/roadmap/

---

## 2026-04-10 - Roadmap Reframed

I restructured my infrastructure engineering roadmap to reflect a clearer long-term direction from hands-on systems work toward architecture, resilience, and complex environment design.

More details: https://eugeneivanov.dev/roadmap/

---

## 2026-04-06 — Fixed Umami tracking issue caused by invalid HTML in Hugo

Resolved a silent analytics failure by identifying a missing closing script tag that broke tracking despite a fully working backend and tunnel.

More details: https://eugeneivanov.dev/journal/troubleshooting/umami-not-tracking-hugo-cloudflare-tunnel/

---

## 2026-04-06 - Minecraft Server with Python Integration

Built and validated a self-hosted Minecraft server with remote access, systemd management, backups, and Python control via RaspberryJuice.

More details: https://eugeneivanov.dev/journal/linux/minecraft-server-proxmox-tailscale-python/

---

## 2026-04-04 - Synology NAS VLAN Migration Troubleshooting

Diagnosed and resolved NAS inaccessibility after VLAN migration, identifying improper shutdown as the root cause rather than a network issue.

More details: https://eugeneivanov.dev/journal/troubleshooting/troubleshooting-synology-nas-vlan-unifi/

---

## 2026-04-03 — Productionizing Umami Analytics with Backup and Recovery

Deployed a self-hosted analytics stack with Cloudflare Tunnel and automated Proxmox backups, turning it into a secure and fully recoverable system.

More details: https://eugeneivanov.dev/journal/linux/umami-cloudflare-tunnel-proxmox-backup/

---

## 2026-03-30 — From Linux to System Thinking

Moved from “learning Linux” to designing a role-based home lab architecture with analytics, monitoring, access, and identity.

More details: https://eugeneivanov.dev/journal/labnotes/home-lab-architecture-from-linux-to-system-thinking/

---

## 2026-03-29 — First Ubuntu Server Deployment in Home Lab

Deployed my first Ubuntu Server VM on Proxmox with static IP, SSH key authentication, and initial system validation.

More details: https://eugeneivanov.dev/journal/linux/first-linux-server-ubuntu-proxmox-installation/

---

## 2026-03-29 — Proxmox First Node Installation Completed

Deployed my first Proxmox VE node on a Dell Micro system with proper BIOS update, storage configuration, and VLAN-based network integration.

More details: https://eugeneivanov.dev/journal/hardware/proxmox-first-node-installation/

---

## 2026-03-28 - Philips Hue VLAN Troubleshooting

Restored Hue after VLAN move by renewing DHCP, assigning fixed IPs, adding a targeted firewall rule, and enabling mDNS.

More details: https://eugeneivanov.dev/journal/troubleshooting/troubleshooting-philips-hue-iot-vlan-unifi/

---

## 2026-03-24 - Correction: Why I Abandoned the Upgrade Path for My First Compute Node 
 
Validated hardware limitations of a Dell Micro system, abandoned upgrade-based strategy, and shifted to a fixed 64GB baseline configuration.  

More details: https://eugeneivanov.dev/journal/hardware/compute-node-upgrade-correction/


---

## 2026-03-20 - Troubleshooting UniFi 10G Link: SFP+ to RJ45

Diagnosed a 1GbE fallback caused by an SFP+ to 2.5G RJ45 negotiation mismatch and restored a stable 10GbE link using SFP+ modules on both ends.

More details: https://eugeneivanov.dev/journal/troubleshooting/unifi-10g-sfp-rj45-mismatch/

---

## 2026-03-19 — Quarantine Network & Port Isolation (UniFi)

Designed and implemented a quarantine VLAN with Layer 3 firewall rules to isolate untrusted devices and convert unused switch ports into controlled, low-trust entry points.

More details: https://eugeneivanov.dev/journal/networking/quarantine-network-unifi/

---

## 2026-03-18 — Home Network Segmentation (VLANs, WiFi, Firewall)

Implemented VLAN-based segmentation with UniFi, configured multiple WiFi networks and firewall rules to isolate traffic and secure the home lab

More details: https://eugeneivanov.dev/journal/networking/home-network-segmentation/

---

## 2026-03-18 — Troubleshooting UniFi WAN Failover After Switching to SFP+  

Resolved a false WAN failover event caused by incorrect WAN role assignment after moving the primary connection to SFP+.  

More details: https://eugeneivanov.dev/journal/troubleshooting/unifi-wan-failover-after-sfp-switch/

---

## 2026-03-18 — Role-Based Access in UniFi

Implemented and documented role-based access in my UniFi home lab by separating Owner and Site Admin responsibilities to apply least privilege in daily operations.

More details: https://eugeneivanov.dev/journal/labnotes/role-based-access-unifi/

---

## 2026-03-18 — 8 Gbps Home Network Validation

Validated an 8 Gbps home network build using Google Fiber and UniFi stack. Achieved near line-rate performance with low latency after physical layer adjustments and manual tuning.

More details: https://eugeneivanov.dev/journal/networking/8gbps-home-network-unifi-google-fiber/

---

## 2026-03-18 - Umami

Planned deployment of Umami (self-hosted analytics) on the Dell node after completing the Linux setup. Chosen for its lightweight, privacy-focused design and to gain hands-on experience deploying a real service. It will serve as the first production-like service in the home lab.

More details: https://eugeneivanov.dev/journal/labnotes/role-based-access-unifi/

---

## 2026-03-17 — Selecting a Compute Node for the Home Infrastructure Lab

Documented compute node selection for home lab. Prioritized architecture and scalability over maximum initial specs.

More details: https://eugeneivanov.dev/journal/hardware/compute-node-selection/

---

## 2026-03-10 — Assembling the Home Lab Rack

Assembled the rack and revised the layout to properly fit the NAS, UPS, and rack shelves.

More details: https://eugeneivanov.dev/journal/hardware/home-lab-rack-assembly/

---

## 2026-03-07 — Installing Home Lab Rack and Patch Panel

Installed the rack patch panel and terminated the house Ethernet cabling.

More details: https://eugeneivanov.dev/journal/hardware/home-lab-rack-patch-panel-installation/

---

## 2026-03-06 — Installing Wall-Mounted Rack

Installed a StarTech 12U wall-mounted rack with a plywood backboard anchored to wall studs.  
Prepared mounting surface for switches, NAS, and UPS.

More details: https://eugeneivanov.dev/journal/hardware/network-rack-backboard/

---

## 2026-03-05 — Planning Home Lab Rack Equipment

Designed the rack layout and selected networking, compute, and power infrastructure components.

More details: https://eugeneivanov.dev/journal/hardware/home-lab-rack-equipment-planning/

---

## 2026-03-05 — Testing Home Ethernet Cabling

Tested existing Ethernet wiring using a Klein Tools VDV501-851 cable tester.  
Verified cable map, continuity, and wiring order for multiple wall ports.

More details: https://eugeneivanov.dev/journal/networking/home-network-cable-testing/
