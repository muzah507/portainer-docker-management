# 🐳 Docker Portainer Management

A lightweight Docker management environment using Portainer Community Edition deployed on a dedicated Ubuntu Server virtual machine.

This project demonstrates centralized container management for homelab infrastructure and self-hosted services using Docker and Portainer CE.

The setup is designed to simulate a small production-style container management server commonly used in:
- Homelab environments
- Self-hosted infrastructures
- Small business deployments
- Development environments

---

# 📌 Project Overview

This repository provides a simple and organized Docker management server capable of:
- Managing Docker containers
- Deploying container stacks
- Monitoring running services
- Managing self-hosted applications
- Simplifying Docker administration

Instead of managing containers only through CLI, this project introduces a web-based infrastructure management approach using Portainer.

---

# 🖥️ Infrastructure Stack

| Component | Technology |
|---|---|
| Hypervisor | Proxmox / VirtualBox / VMware |
| Operating System | Ubuntu Server 24.04 LTS |
| Container Runtime | Docker |
| Management Platform | Portainer CE |
| Deployment Method | Docker Compose |

---

# 🌐 Network Topology

```text id="5zbmb6"
                     INTERNET
                         │
                    ISP Router
                         │
                    MikroTik Router
                         │
               ┌─────────┴─────────┐
               │                   │
        Portainer VM         Docker Services
        Ubuntu Server        Jellyfin / Kuma
        Docker + Portainer   Pi-hole / NAS
```
---

# ✨ Features

## 🐳 Container Management

- Docker Container Administration
- Stack Deployment
- Container Logs Access
- Container Lifecycle Management
- Image Management

---

## 🖥️ Infrastructure

- Dedicated Docker Management VM
- Dockerized Deployment
- Persistent Storage
- Lightweight Resource Usage
- Automatic Restart Policy

---

## 🌐 Management Capabilities

- Web-based Docker Administration
- Multi-container Visibility
- Docker Stack Management
- Simplified Infrastructure Operations

---

## 🛡️ Reliability

- Isolated Management Environment
- Easy Backup Strategy
- Simple Scalability
- Clean Infrastructure Separation

---

# ⚙️ VM Specifications

| Resource | Allocation |
|---|---|
| vCPU | 1 Core |
| RAM | 1 GB |
| Storage | 10 GB |
| Network | Bridged Adapter |
| OS | Ubuntu Server |

This setup is optimized for lightweight homelab usage.

---

# 🔐 Security Recommendations

Recommended improvements:

- Use HTTPS reverse proxy
- Restrict dashboard access
- Use VPN-only management access
- Enable firewall rules
- Use strong administrator credentials

---

# 📈 Future Improvements

Planned upgrades:

- Reverse Proxy with Nginx
- HTTPS using Let's Encrypt
- Multi-host Docker management
- Docker Swarm support
- Monitoring integration
- WireGuard VPN access

---

# 🎯 Portfolio Value

This project demonstrates practical skills related to:

- Linux Administration
- Docker Management
- Infrastructure Operations
- Self-hosted Services
- Container Deployment
- Technical Documentation

Suitable for:

- Junior SysAdmin portfolios
- DevOps learning portfolios
- Infrastructure Engineer portfolios
- Homelab projects

---

# 📄 License

MIT License
