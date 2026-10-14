# Students — SKYWATER_PDK

**Project:** SKYWATER_PDK  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `7198cf647113f56041e02abf3eb623692820c5e1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b66bb1ca18b2188ebb35f76fe30618313cf1fba30e2b6b3ca3317ccfbe737356`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `7198cf647113f56041e02abf3eb623692820c5e1`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `b66bb1ca18b2188ebb35f76fe30618313cf1fba30e2b6b3ca3317ccfbe737356`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
