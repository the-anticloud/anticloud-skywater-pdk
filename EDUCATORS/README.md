# Educators — SKYWATER_PDK

**Project:** SKYWATER_PDK  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `7198cf647113f56041e02abf3eb623692820c5e1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b66bb1ca18b2188ebb35f76fe30618313cf1fba30e2b6b3ca3317ccfbe737356`  
**Date:** October 2026

## Teaching with SKYWATER_PDK

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `b66bb1ca18b2188ebb35f76fe30618313cf1fba30e2b6b3ca3317ccfbe737356` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
