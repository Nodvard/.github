## Nodvard

<a href="https://nodvard.com"><img src="https://nodvard.com/assets/og/start-en.jpg" alt="Nodvard Deck: your homelab on one page" width="720"></a>

Self-hosted tools for your homelab – built and maintained in Germany. The interfaces are currently in German.

### Products

| | |
|---|---|
| **[Nodvard Deck](https://github.com/nodvard/deck)** | Homelab dashboard: servers, Docker containers, Proxmox VMs and backups in one place, set up entirely in the web interface. Includes **Nodvard Shield** (antivirus and update center for your servers). Runs on Raspberry Pi and x86. *Public beta.* |
| **[Nodvard Dock](https://github.com/nodvard/dock)** | Lean edition with only the Docker part of Deck: containers and Compose stacks on all your servers, agentless over SSH, moves stacks from Portainer CE in one click. *Public beta.* |

<p>
  <img src="https://nodvard.com/assets/img/docker.webp" alt="Docker containers of all servers in Nodvard Deck" width="360">
  <img src="https://nodvard.com/assets/img/backups.webp" alt="Backup overview in Nodvard Deck" width="360">
</p>

<sub>Screenshots with demo data.</sub>

On the roadmap: **Nodvard Link** (open interface for other tools) and an Android app.

### Get started

```bash
mkdir ~/nodvard-deck && cd ~/nodvard-deck
curl -fsSL -o compose.yml https://raw.githubusercontent.com/nodvard/deck/main/deploy/compose.standalone.yml
docker compose up -d
```

Then open `http://<your-server>:8080` and follow the setup assistant. The interface is currently in German.

### License

Free for personal and other noncommercial use under the [PolyForm Noncommercial License 1.0.0](https://github.com/nodvard/deck/blob/main/LICENSE). Commercial use is not permitted without separate permission.

Feedback and bug reports are welcome as [issues](https://github.com/nodvard/deck/issues) or on [Discord](https://discord.gg/gTTs7qMabt) · Contact: kontakt@nodvard.com · [Website](https://nodvard.com) · [Legal notice / Impressum](https://nodvard.com/impressum.html) · [Privacy](https://nodvard.com/datenschutz.html)
