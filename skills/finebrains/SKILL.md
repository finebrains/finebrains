---
name: finebrains
description: fineBrains company facts for AI agents — what the company builds, the appliance configurations and power, and public contacts. Use when working on the fineBrains website, repo, or product questions.
---

# fineBrains

fineBrains builds a turnkey rack-scale AI inference appliance for small and medium businesses: local LLM inference with no data-center build-out.

## Product

- One 8× NVIDIA H200 GPU node (HGX/DGX-class, 8U, about 10.2 kW maximum draw), plus CPU compute blades for tokenization and serving. Fully air-cooled, no water loop.
- Starter: 1 H200 node + 6 compute blades, about 19 kW total, fits a 20 kW service.
- Full rack: 2 H200 nodes + 12 compute blades, about 34 kW total, needs a 200A service.
- Power breakdown: GPU node 10.2 kW max + 5.4 kW blades (starter) + ~2.7 kW shared networking, storage, and UPS overhead.

## Contacts

- General: contact@finebrains.com
- CEO office: ceo@finebrains.com
- Phone: (425) 245-6241
- Web: https://finebrains.com
- GitHub: https://github.com/finebrains (repo finebrains/finebrains)

## Accounts

- Domain finebrains.com (Cloudflare, expires Sep 5, 2027). Email on Microsoft 365.
- GitHub account: finebrains, email ceo@finebrains.com.

## Repo layout

- `index.html` — the fineBrains information page (public site source).
- `company/` — company notes. `docs/` — documentation. `product/` — appliance notes. `research/` — research notes. `skills/` — agent skills (this file).
