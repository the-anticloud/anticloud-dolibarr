# Educators — DOLIBARR

**Project:** DOLIBARR  
**Category:** CONSULTANCY  
**Upstream:** https://github.com/dolibarr/dolibarr  
**Pinned commit:** `f669c0a10753ccbf480c3dcf389c985d073fb589`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `671eeb5bde7267689be7fa325f5de81009f2f4b963397186c7b03dcc42676409`  
**Date:** October 2026

## Teaching with DOLIBARR

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `671eeb5bde7267689be7fa325f5de81009f2f4b963397186c7b03dcc42676409` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
