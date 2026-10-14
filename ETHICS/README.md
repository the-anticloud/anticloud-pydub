# Ethics — PYDUB

**Project:** PYDUB  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/jiaaro/pydub  
**Pinned commit:** `103e339d3bc7a9a58a9f1de65f7d8074659b5f5a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1d5cac60d499fdf88cbb145bb86084dc1a72aef4a2344f586a8dfc0922873a26`  
**Date:** October 2026

## Position

PYDUB is packaged for offline deployment with a verifiable audit trail. The
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
