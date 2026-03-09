# Hey, I'm James

Cloud lead by day, homelab hoarder by night.

I run a three-node Proxmox cluster, a UniFi network with more VLANs than users, and 30+ LXC containers doing everything from reverse proxying to tracking petrol prices. It's a data centre if you squint.

## What I'm Working On

**[FuelTrack](https://github.com/beaglemoo/fueltrack)** - Pulls fuel prices from all 7,400 UK petrol stations via the GOV.UK API, stores them in InfluxDB, and publishes a searchable page updated every 4 hours. [See it live](https://sillymoo.dev/uk-fuel-prices/)

**[The Moo Log](https://sillymoo.dev)** - Blog documenting the homelab builds, the late-night debugging sessions, and the overengineered solutions to problems that didn't need solving.

## The Stack

```
Proxmox VE (3 nodes)    |  Caddy (reverse proxy, DMZ + internal)
LXC Containers (30+)    |  InfluxDB + Grafana (monitoring)
UniFi (UCG Fiber)       |  Ghost (blog)
TrueNAS (storage)       |  CrowdSec (security)
```

## Projects

| Repo | What It Does |
|------|-------------|
| [fueltrack](https://github.com/beaglemoo/fueltrack) | UK fuel price tracker - GOV.UK API to InfluxDB to Ghost |
| [ghost-mcp-server](https://github.com/beaglemoo/ghost-mcp-server) | Patched Ghost MCP server for Claude Code |
