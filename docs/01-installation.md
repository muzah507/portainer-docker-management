# Ubuntu Server Installation

This document explains how to prepare the dedicated Docker management VM for Portainer deployment.

---

# System Requirements

| Resource | Minimum |
|---|---|
| CPU | 1 vCPU |
| RAM | 1 GB |
| Storage | 10 GB |

---

# Install Ubuntu Server

Recommended version:
- Ubuntu Server 24.04 LTS

During installation:
- Enable OpenSSH Server
- Use bridged networking

---

# Update System

```bash
sudo apt update && sudo apt upgrade -y
