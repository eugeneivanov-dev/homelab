# Engineering Journal

Short notes about infrastructure work, lab experiments, and physical network setup.

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
