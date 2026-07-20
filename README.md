# Lido

Solo Bitcoin mining pool for [Umbrel](https://umbrel.com). Runs your own Stratum V1 + V2 pool against your Bitcoin node — full block reward if you find a block, no pool fees.

Dashboard demo: https://lido.wtf/

Source: pool [`lido`](https://github.com/KevinGuest/lido) · UI [`lido-ui`](https://github.com/KevinGuest/lido-ui)

## Install

1. Install the **Bitcoin** app on umbrelOS (required dependency).
2. App Store → Community App Stores → add:

```
https://github.com/KevinGuest/lido-app
```

3. Install **Lido**.

Point miners at the Connect details in the app:

| Port | Service |
| --- | --- |
| **2300** | Web UI |
| **2301** | Stratum V1 |
| **2302** | Stratum V2 |
| **2299** | Pool API (internal) |

## What’s included

- Modern dashboard (hashrate, workers, difficulty)
- Stratum V1 + Stratum V2 (Noise / Mining Protocol)
- Discord and Telegram alerts for blocks, struggling miners, and digests
- Umbrel home-screen widgets

Images: `ghcr.io/kevinguest/lido-ui` + `ghcr.io/kevinguest/lido` (see `lido-app/docker-compose.yml` for pinned versions).
