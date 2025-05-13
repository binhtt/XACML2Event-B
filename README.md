# XACML2Event-B: A Formal Framework for Verifying XACML Policies using Event-B

This repository contains the implementation, case studies, and reproducibility materials for the paper:

**"XACML2Event-B: A formal approach to verifying the consistency of XACML policies using Event-B"**  
(submitted to *International Journal on Software Tools for Technology Transfer*).

---

## 📌 Overview

**XACML2Event-B** is a tool-supported framework that enables formal verification of access control policies specified in [XACML 3.0](https://docs.oasis-open.org/xacml/3.0/). The tool chain transforms policies from:
1. **Textual rules** →  
2. **XACML format** →  
3. **Event-B models**,  
which are then automatically verified using the [Rodin platform](https://www3.hhu.de/stups/rodin.html).

The approach supports:
- Static conflict detection via invariant analysis,
- Proof-based validation of semantic correctness,
- Completeness checking for access request coverage.

---


