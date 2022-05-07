# Home Lab

## Applications

* Cloudflared
* Traefik
* Grafana w/ Loki
* Home Assistant
* Portainer
* Transmission
* MiniDLNA

## Cloudflare

```
docker compose run cloudflared login
docker compose run cloudflared tunnel create <name>
docker compose run cloudflared tunnel route dns <id> <domain>
```

