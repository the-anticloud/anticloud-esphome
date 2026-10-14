# Ethics — ESPHOME

**Project:** ESPHOME  
**Category:** CONSUMER_APPLIANCES  
**Upstream:** https://github.com/esphome/esphome  
**Pinned commit:** `8617368294e43110d2139f6125c30cd7a95b5a2c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `06dd668bd61254ac37273d677c4e302f88cdaf06917708cee0a8b3897966c12d`  
**Date:** October 2026

## Position

ESPHOME is packaged for offline deployment with a verifiable audit trail. The
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
