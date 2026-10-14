# Students — DOLIBARR

**Project:** DOLIBARR  
**Category:** CONSULTANCY  
**Upstream:** https://github.com/dolibarr/dolibarr  
**Pinned commit:** `f669c0a10753ccbf480c3dcf389c985d073fb589`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `671eeb5bde7267689be7fa325f5de81009f2f4b963397186c7b03dcc42676409`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `f669c0a10753ccbf480c3dcf389c985d073fb589`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `671eeb5bde7267689be7fa325f5de81009f2f4b963397186c7b03dcc42676409`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
