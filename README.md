# Docker Stacks

A collection of lightweight Docker stacks and self-hosted infrastructure setups focused on simplicity, monitoring, security and automation.

## Included Stacks

- Uptime Kuma
- Portainer
- Nginx Proxy Manager
- Pi-hole
- Grafana
- Dozzle
- Watchtower

---

## Stack Overview

### Uptime Kuma
Self-hosted uptime monitoring and status page solution.

### Portainer
Web-based Docker and container management interface.

### Nginx Proxy Manager
Reverse proxy manager with automatic SSL certificates.

### Pi-hole
Network-wide ad blocking and DNS filtering.

### Grafana
Metrics visualization and monitoring dashboards.

### Dozzle
Real-time Docker log viewer.

### Watchtower
Automatic Docker container updates.

---

## Quick Start

Clone the repository:

```bash
git clone https://github.com/RootSignalOps/docker-stacks.git
```

Go into a stack directory:

```bash
cd docker-stacks/uptime-kuma
```

Run the stack:

```bash
docker compose up -d
```

---

## Goals

- Lightweight infrastructure
- Easy deployments
- Self-hosted tooling
- Monitoring and observability
- Docker-first workflows

---

## Notes

Most stacks require Docker and Docker Compose installed on the host system.

Some services may also require:
- Open ports
- Domain configuration
- Reverse proxy setup
- Persistent storage volumes

---

## License

MIT License
