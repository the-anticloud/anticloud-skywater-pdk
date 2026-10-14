# Ethics — SKYWATER_PDK

**Project:** SKYWATER_PDK  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `7198cf647113f56041e02abf3eb623692820c5e1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b66bb1ca18b2188ebb35f76fe30618313cf1fba30e2b6b3ca3317ccfbe737356`  
**Date:** October 2026

## Position

SKYWATER_PDK is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
