# Educators — PYDUB

**Project:** PYDUB  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/jiaaro/pydub  
**Pinned commit:** `103e339d3bc7a9a58a9f1de65f7d8074659b5f5a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1d5cac60d499fdf88cbb145bb86084dc1a72aef4a2344f586a8dfc0922873a26`  
**Date:** October 2026

## Teaching with PYDUB

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `1d5cac60d499fdf88cbb145bb86084dc1a72aef4a2344f586a8dfc0922873a26` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
