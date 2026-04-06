# AdGuard Home

Network-wide ad-blocking DNS server.

## Quick Start

```bash
cp .env.example .env
docker compose up -d
```

## Setup (First Time)

1. Connect to VPN
2. Open `http://10.8.1.3:3000`
3. Complete setup wizard (create your own user/password)
4. Set upstream DNS to: `10.8.1.4` (Unbound)

## Ports

| Port | Protocol | Service |
|------|----------|---------|
| 3000 | TCP | Web UI |

## Network

- Container IP: `10.8.1.3`
- Upstream DNS: `10.8.1.4` (Unbound)

## By Brazwed
