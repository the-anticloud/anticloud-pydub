# Students — PYDUB

**Project:** PYDUB  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/jiaaro/pydub  
**Pinned commit:** `103e339d3bc7a9a58a9f1de65f7d8074659b5f5a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1d5cac60d499fdf88cbb145bb86084dc1a72aef4a2344f586a8dfc0922873a26`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `103e339d3bc7a9a58a9f1de65f7d8074659b5f5a`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `1d5cac60d499fdf88cbb145bb86084dc1a72aef4a2344f586a8dfc0922873a26`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
