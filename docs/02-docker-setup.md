# Docker Setup

Install Docker Engine and Docker Compose.

---

# Install Docker

```bash
sudo apt update
sudo apt install docker.io docker-compose -y
```

---

# Enable Docker
```bash
sudo systemctl enable docker
sudo systemctl start docker
```

---

# Verify Docker
```bash
docker --version
docker ps
```
