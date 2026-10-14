# Ethics — DOLIBARR

**Project:** DOLIBARR  
**Category:** CONSULTANCY  
**Upstream:** https://github.com/dolibarr/dolibarr  
**Pinned commit:** `f669c0a10753ccbf480c3dcf389c985d073fb589`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `671eeb5bde7267689be7fa325f5de81009f2f4b963397186c7b03dcc42676409`  
**Date:** October 2026

## Position

DOLIBARR is packaged for offline deployment with a verifiable audit trail. The
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
