# Educators — ESPHOME

**Project:** ESPHOME  
**Category:** CONSUMER_APPLIANCES  
**Upstream:** https://github.com/esphome/esphome  
**Pinned commit:** `8617368294e43110d2139f6125c30cd7a95b5a2c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `06dd668bd61254ac37273d677c4e302f88cdaf06917708cee0a8b3897966c12d`  
**Date:** October 2026

## Teaching with ESPHOME

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `06dd668bd61254ac37273d677c4e302f88cdaf06917708cee0a8b3897966c12d` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
