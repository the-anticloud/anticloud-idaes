# How to Update — IDAES

**Project:** `IDAES`
**Category:** CHEMICAL_PRODUCTION
**Domain:** chemical production and simulation
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
IDAES --version
IDAES check-update
```

### Applying Updates
```bash
pip install --upgrade IDAES
```

### Rolling Back
```bash
pip install IDAES==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
