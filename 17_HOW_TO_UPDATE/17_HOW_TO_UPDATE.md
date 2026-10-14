# How to Update — CCSI_TOOLSET

**Project:** `CCSI_TOOLSET`
**Category:** CARBON_CAPTURE
**Domain:** carbon capture, utilization, and storage
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
CCSI_TOOLSET --version
CCSI_TOOLSET check-update
```

### Applying Updates
```bash
pip install --upgrade CCSI_TOOLSET
```

### Rolling Back
```bash
pip install CCSI_TOOLSET==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
