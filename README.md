# docker-compose stacks

A curated collection of Docker Compose stacks I use for homelab and quick deployments. Each subfolder contains an isolated stack with its own `compose.yaml` and (optionally) an `.env.example`.

> **Heads-up**  
> Use **Docker Compose v2** (`docker compose …`) and the modern **Compose Specification** (no `version:` key). See the official docs for current syntax and CLI.  [oai_citation:0‡Docker Documentation](https://docs.docker.com/compose/?utm_source=chatgpt.com)

---

## What’s inside

Stacks currently included (folder = stack):

- `corentinth/it-tools` – handy web IT tools  
- `cupcakearmy/cryptgeon` – ephemeral secrets pastebin  
- `docker.io` – base examples / helpers  
- `dockurr/windows` – Windows VM in Docker  
- `favonia/cloudflare-ddns` – Cloudflare DDNS updater  
- `homeassistent` – Home Assistant  
- `iv-org/invidious` – YouTube front-end  
- `linuxserver` – LinuxServer.io apps (misc)  
- `matomo` – web analytics  
- `metube` – web video downloader  
- `mpepping/cyberchef` – CyberChef  
- `ms-jpq/docker-time-machine` – Time Machine over SMB  
- `olveix/satisfactory-server` – game server  
- `pglombardo/PasswordPusher` – password drop links  
- `pihole` – network-wide ad/tracker blocking  
- `portainer/portainer-ce` – Docker UI  
- `qualys/jira-integration` – Qualys ↔ Jira  
- `quay/keycloak` – identity & access mgmt  
- `registry` – private container registry  
- `sissbruecker/linkding` – bookmarks  
- `stirlingtools/stirling-pdf` – PDF toolbox  
- `telekom-security/tpot` – honeypot platform  
- `valiantlynx/ollama` – local LLM runtime

Check each subfolder for service-specific notes and environment variables before starting. (Folder list based on the repository tree.)  [oai_citation:1‡GitHub](https://github.com/koensmink/docker-compose)

---

## Prerequisites

- Docker Engine + Docker Compose v2 (Docker Desktop on macOS/Windows already includes this).  [oai_citation:2‡Docker Documentation](https://docs.docker.com/?utm_source=chatgpt.com)
- Basic understanding of Compose files and `.env` handling.  [oai_citation:3‡Docker Documentation](https://docs.docker.com/reference/compose-file/?utm_source=chatgpt.com)

---

## Quick start (any stack)

1. **Clone**
   ```bash
   git clone https://github.com/koensmink/docker-compose.git
   cd docker-compose
