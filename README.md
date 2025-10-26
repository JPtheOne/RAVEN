# RAVEN — Research & Analysis Virtual Environment Network

**Forensic Environment for Network Research & Incident Response**

A compact, reproducible lab for malware analysis, reverse engineering, and basic enterprise simulation intended to run throuh Proxmox on a NUC.  

Designed to be accessible through VPN and SSH. Intended for learning, detection testing, and building repeatable playbooks.

---

## What this repo contains
- **JOURNAL.md** — step-by-step notes and troubleshooting from the build.  
- **scripts/** — minimal, idempotent helpers to prepare host networking, create VMs, and enable VNC autostart.  
- **examples/** — sample VM config snippets (Proxmox `.conf`), systemd VNC service examples, architecture notes.  
- **docs/** — network architecture, Tailscale instructions, and optional tooling notes.


![alt text](image.png)