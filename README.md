<div align="center">

# Security Risk Assessment for the 'Horribly Insecure Web Application' (HIWA)

**Turning the HIWA vulnerabilities into a GRC-style risk report**

![Status](https://img.shields.io/badge/status-in_progress-81E2F2?style=for-the-badge)
![Framework](https://img.shields.io/badge/framework-NIST_SP_800--53-4DA8FF?style=for-the-badge)
![Findings](https://img.shields.io/badge/findings-7_rated-0D1B2A?style=for-the-badge)

</div>

---

## Scope & Assumptions

HIWA is a **Horribly Insecure Web Application** and it is intentionally a vulnerable web application built by my Application Security professor for a CTF (Capture-the-flag) exercise ([HIWA information](https://github.com/keesL/hiwa)). All findings in this report come from doing the exercises.

To assess business impact, I will assume HIWA is the storefront for a **potential small online retailer** that simply just stores customer accounts and their product data. This business setting is also entirely hypothetical and used only for scenario purposes; the vulnerabilities themselves are real.

*The challenge answers that contained the (flag values) are intentionally left out of this repository because my purpose here is not to reveal those challenge answers to you.*

## Where to Find Everything

Each stage of the assessment is added to its own folder as it's completed:

- **`findings/`** · risk ratings for each finding 
- **`mapping/`** · NIST SP 800-53 control mapping
- **`policy/`** · secure coding policy
- **`report/`** · risk register and executive summary

---
