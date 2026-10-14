# Independent Insurance — SKYWATER_PDK

**Project:** SKYWATER_PDK  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `7198cf647113f56041e02abf3eb623692820c5e1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b66bb1ca18b2188ebb35f76fe30618313cf1fba30e2b6b3ca3317ccfbe737356`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | SKYWATER_PDK with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `b66bb1ca18b2188ebb35f76fe30618313cf1fba30e2b6b3ca3317ccfbe737356`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
