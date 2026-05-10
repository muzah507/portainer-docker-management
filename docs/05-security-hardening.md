# Security Hardening

Basic security recommendations for Portainer deployment.

---

# Firewall Configuration

```bash
sudo ufw allow 22/tcp
sudo ufw allow 9000/tcp
```

---

# Use Strong Credentials

Recommendations:
- Minimum 12 characters
- Mixed symbols and numbers

---

# Restrict Access

Recommended:
- VPN-only access
- Reverse proxy authentication
- Local network only

---

# Docker Security

Recommendations:
- Keep Docker updated
- Remove unused containers
- Remove unused images
- Monitor logs regularly

---

# Backup Strategy

Backup:
- Portainer data volume
- Docker Compose files
- Environment variables

---

# Future Improvements

Possible upgrades:
- HTTPS reverse proxy
- WireGuard VPN
- Multi-host management
- Monitoring integration
