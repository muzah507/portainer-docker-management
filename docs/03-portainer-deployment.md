# Portainer Deployment

Deploy Portainer using Docker Compose.

---

# Navigate to Config Directory

```bash
cd configs
```

---

# Start Portainer

```bash
docker compose up -d
```

---

# Verify Container

```bash
docker ps
```

Expected container:
- portainer

---

# Access Dashboard

```text
http://SERVER-IP:9000
```

---

# Initial Setup

Create:
- Administrator username
- Strong password

Then connect:
- Local Docker environment
