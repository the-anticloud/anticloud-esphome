# Students — ESPHOME

**Project:** ESPHOME  
**Category:** CONSUMER_APPLIANCES  
**Upstream:** https://github.com/esphome/esphome  
**Pinned commit:** `8617368294e43110d2139f6125c30cd7a95b5a2c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `06dd668bd61254ac37273d677c4e302f88cdaf06917708cee0a8b3897966c12d`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `8617368294e43110d2139f6125c30cd7a95b5a2c`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `06dd668bd61254ac37273d677c4e302f88cdaf06917708cee0a8b3897966c12d`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
