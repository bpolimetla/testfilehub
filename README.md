# Testfilehub

**Author:** Bhavani Polimetla  
**Date:** Feb 13, 2026

---

## Problem Statement

To perform a speed test from a browser, a 10MB file is required for download.

## Solution 1: Use Readily Available Files

- [https://testfilehub.github.io/](https://testfilehub.github.io/) provides files, but I can't trust them.
- Therefore, I created and uploaded my own file for personal use.

## Solution 2: Generate and Upload to Own GitHub Location

Generate a random `.bin` file of size 10MB:

```bash
dd if=/dev/urandom of=10MB.bin bs=1M count=10
```

This command creates:

- True random data
- Exactly 10MB
- Not compressible
- Perfect for speed testing

---
