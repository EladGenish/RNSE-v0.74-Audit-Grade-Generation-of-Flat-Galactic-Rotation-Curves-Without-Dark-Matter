# RNSE — Recursive Null-Seed Engine (v0.74-AUDIT)

**Status:** Publication-Ready · Reproducible · IP-Protected  
**Author:** Elad Genish  
**Date:** January 2026  

RNSE (Recursive Null-Seed Engine) is a deterministic computational framework that
demonstrates how **flat galactic rotation curves**—normally attributed to Dark Matter—
can emerge from **pure recursive computation**, without adding mass, fitting parameters,
or trained models.

This repository provides a **complete audit-grade evidence package**:
every result is reproducible, cryptographically verifiable, and suitable for
independent validation.

---

## Core Claim

> Flat rotation curves can emerge from recursive computational geometry alone.

Classical physics predicts a strong velocity decline at the edges of galaxies.
Observations show this decline does **not** occur.
RNSE reproduces this flat velocity profile **without** invoking Dark Matter.

---

## Key Result (v0.74)

- Particle count: **10,000**
- Median radius: **~61 kpc**
- Classical expectation: **>50% velocity drop**
- RNSE result: **~0.74% velocity drop**
- Interpretation: **FLAT rotation curve**
- Determinism: **Same seed = identical output**
- Verification: **SHA-256 audit digest**

---

## What This Repository Contains

### Included
- Deterministic RNSE execution
- Galaxy-scale structure generation
- Rotation curve analysis
- Cryptographic audit trail
- Publication-ready outputs
- Independent verification protocol

### Not Included
- Optimized GPU kernels
- Commercial API layers
- Proprietary extensions
- Patent-pending optimizations

This separation is intentional and protects IP while preserving scientific verification.

---

## Reproducibility Guarantee

RNSE is **fully deterministic**.

To verify independently:
1. Run the test suite
2. Observe the reported metrics
3. Compare the SHA-256 digest
4. Re-run with the same seed
5. Confirm the digest matches exactly

If the hash matches, the result is verified.

---

## Quick Start

```bash
python rnse_test_suite.py
