# How to Update — PI

**Project:** `PI`
**Category:** CONSUMER_ELECTRONICS
**Domain:** consumer electronics
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
PI --version
PI check-update
```

### Applying Updates
```bash
pip install --upgrade PI
```

### Rolling Back
```bash
pip install PI==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
