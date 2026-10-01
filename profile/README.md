## Nodvard

Self-hosted tools for your homelab – built and maintained in Germany.

### Products

| | |
|---|---|
| **[Nodvard Deck](https://github.com/nodvard/deck)** | Homelab dashboard: servers, Docker containers, Proxmox VMs and backups in one place, set up entirely in the web interface. Includes **Nodvard Shield** (antivirus and update center for your servers). Runs on Raspberry Pi and x86. *Public beta.* |
| **Nodvard Link** | Open interface so other dashboards and tools can talk to Nodvard products. *Planned.* |
| **Nodvard App** | Android app for Nodvard Deck. *Planned.* |

### Get started

```bash
mkdir ~/nodvard-deck && cd ~/nodvard-deck
curl -fsSL -o compose.yml https://raw.githubusercontent.com/nodvard/deck/main/deploy/compose.standalone.yml
docker compose up -d
```

Then open `http://<your-server>:8080` and follow the setup assistant. The interface is currently in German.

### License

Free for personal and other noncommercial use under the [PolyForm Noncommercial License 1.0.0](https://github.com/nodvard/deck/blob/main/LICENSE). Commercial use is not permitted without separate permission.

Feedback and bug reports are welcome as [issues](https://github.com/nodvard/deck/issues) · Contact: kontakt@nodvard.com
