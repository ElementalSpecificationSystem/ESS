# Elemental Specification System (ESS)

**An open, copyright-free construction work-results taxonomy for North American practice.**

[![License: ODbL](https://img.shields.io/badge/License-ODbL_1.0-blue.svg)](https://opendatacommons.org/licenses/odbl/)
[![Version](https://img.shields.io/badge/Version-1.0-green.svg)]()
[![Status](https://img.shields.io/badge/Status-Public_Review-orange.svg)]()

---

## What ESS Is

ESS is a numbered classification taxonomy that organizes construction work results for use in project manuals, cost models, and building information workflows. It is designed for architects, specifiers, engineers, contractors, estimators, owners, and software developers.

**It is free. It is open. It belongs to the community.**

Anyone may use ESS, implement it in software, build upon it, or adapt it — without a license, fee, or permission request — subject to the ShareAlike terms of the Open Database License (ODbL 1.0).

---

## What ESS Is Not

- Not a specification writing platform
- Not a software product
- Not a CSI or CSC publication or derivative work
- Not subject to copyright by any contributor, sponsor, or steward
- Not controlled by any single entity

---

## Why ESS Exists

The North American construction industry has relied on a single licensed taxonomy — MasterFormat® — as the organizational spine of project manuals, cost codes, and specification software for over six decades. That taxonomy is a joint copyright of the Construction Specifications Institute (CSI) and Construction Specifications Canada (CSC), governed by an end-user license agreement that restricts reproduction, derivative works, and software integration.

No open alternative has existed — until now.

ESS addresses three specific problems:

1. **Software licensing cost.** Platforms implementing MasterFormat pay annual fees that accumulate across product suites and are passed to practitioners and owners. ESS eliminates that dependency.

2. **AI integration friction.** AI-assisted specification authorship is emerging as standard practice. AI tools cannot freely reproduce or derive from licensed taxonomies. ESS removes that constraint structurally.

3. **No open fallback.** When a community's primary infrastructure is owned by a single institution, there is no resilience. ESS is that fallback — and it competes on merit.

---

## Structure

ESS is organized by **work results** — what is being constructed — consistent with the logic of North American project manual practice. It uses a six-digit numbering system with two-digit division identifiers and four-digit section identifiers.

```
Division XX 00 00   — Major work category
  Section XX XX 00  — Work type
    Section XX XX XX — Specific work result
```

ESS contains **48 active divisions** across five groups:

| Group | Divisions | Scope |
|---|---|---|
| Group 00 | 00–01 | Procurement, Contracting, and General Requirements |
| Group 10 | 10–19 | Facility Construction |
| Group 20 | 20–29 | Facility Services |
| Group 30 | 30–39 | Site and Infrastructure |
| Group 40 | 40–49 | Process and Specialized Construction |

Divisions 15–19 and select others are reserved for future expansion.

Full taxonomy: see [`ESS_Taxonomy_v1.0.csv`](ESS_Taxonomy_v1.0.csv) and [`ESS_Taxonomy_v1.0.json`](ESS_Taxonomy_v1.0.json)

Advisory MasterFormat crossreference: see [`MASTERFORMAT_CROSSREF.csv`](MASTERFORMAT_CROSSREF.csv)

---

## License

ESS is released under the **Open Database License (ODbL) 1.0**.

Full license text: [`LICENSE.txt`](LICENSE.txt)

**Plain-language summary:**
- You are free to use, share, and adapt ESS
- You must attribute ESS if you use it publicly
- If you create a modified or derivative taxonomy, you must release it under the same open terms
- You may build proprietary software *on top of* ESS — but the taxonomy layer itself must remain open

The ODbL ShareAlike clause is ESS's structural anti-capture mechanism. No entity — including the founding steward, any co-sponsor, or any software vendor — may privatize what the community builds.

---

## Governance

ESS is governed by a Stewardship Council of independent construction industry professionals. No single entity holds more than one seat. No corporate sponsor holds a governance vote.

Full governance terms: see [`CHARTER.md`](CHARTER.md)

---

## Using ESS in Software

Software vendors, specification platforms, cost modeling systems, and BIM tools are explicitly invited to implement ESS without fee or permission. Implementation is the point.

ESS is also submitted to the **buildingSMART Data Dictionary (bSDD)** as a free public classification system, enabling IFC-native integration.

If you implement ESS in a product, please open an issue or pull request to add yourself to the [Implementations list](IMPLEMENTATIONS.md). This helps the community find conforming tools.

---

## Contributing

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for how to propose additions, corrections, or amendments to the taxonomy.

Short version:
- **Minor corrections** (typos, title clarifications): open a pull request
- **New section proposals**: open an issue using the Section Proposal template
- **Structural amendments**: open an issue; subject to 60-day public comment and Stewardship Council vote

---

## Project Status

ESS v1.0 is currently in **public review**. The Stewardship Council will consider all substantive comments received during the review period before issuing v1.0 final.

---

## Founding Steward

**Eric Letbetter, AIA, CCS, SCIP**  
Letbetter Ink — Alpharetta, Georgia  
[letbetterink.com](https://letbetterink.com)

---

*ESS is not affiliated with, endorsed by, or derived from any publication of the Construction Specifications Institute (CSI), Construction Specifications Canada (CSC), or any other standards body. MasterFormat® is a registered trademark of CSI and CSC.*
