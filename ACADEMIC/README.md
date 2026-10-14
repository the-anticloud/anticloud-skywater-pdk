# Academic Use — SKYWATER_PDK

**Project:** SKYWATER_PDK  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `7198cf647113f56041e02abf3eb623692820c5e1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b66bb1ca18b2188ebb35f76fe30618313cf1fba30e2b6b3ca3317ccfbe737356`  
**Date:** October 2026

## Scope

SKYWATER_PDK is available for academic research under the Apache 2.0 terms of the
Anticommons 0.1.0 dual licence. Citation details are in `23_HOW_TO_CITE`.

## What is available to researchers

- The full upstream source, pinned at `7198cf647113f56041e02abf3eb623692820c5e1`
- The 16-check assurance register with per-check evidence and hashes
- The AIOSS ledger attesting the project artifacts
- Benchmark output in `BENCH.json`

## Reproducing the result

```
python tools/run_bench.py --out BENCH.json
```

Then recompute any row's SHA3-256 from `ISOLATED_LAB_RESULTS/04_Evidence/`.

## Contact

lois@0-1.gg · 0-1.gg
