# SocialBlock L1 Testnet — GitHub Repository

This repository contains the **SocialBlock L1 Testnet** scaffold, ready for local development, Docker deployment, and future mainnet promotion.

## Overview
SocialBlock L1 is a sovereign Cosmos SDK + CometBFT blockchain that integrates:
- **AI Reputation Proof (ARP)** consensus weighting
- **zkID** sybil resistance
- **SocialFi-native** token gating, campaigns, and AI agent economy

## Quick Start

### Local Single Node
```bash
make localnet
```

### Docker Multi-node
```bash
cd docker/compose
docker compose up -d --build
```

## Docs
See `/docs` for:
- Architecture diagram
- ARP specification
- API endpoints

## License
Apache 2.0

---
Generated on 2025-08-14
