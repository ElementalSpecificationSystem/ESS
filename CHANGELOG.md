# ESS Changelog

All notable changes to the Elemental Specification System are documented here.

Version numbering follows a two-tier model:
- **Major versions** (1.0, 2.0): structural changes — renumbering, division additions/deletions, organizational logic changes. Require 60-day public comment and Stewardship Council supermajority.
- **Minor versions** (1.1, 1.2): additions, corrections, editorial clarifications. Require simple majority of Stewardship Council.

---

## [1.0] — 2026-06-01 — Initial Publication

### Added
- Complete ESS taxonomy: 48 active divisions, 931 sections across five groups
- Founding Charter (CHARTER.md) establishing governance, licensing, and anti-capture provisions
- MasterFormat cross-reference (MASTERFORMAT_CROSSREF.csv) — advisory, not normative
- Contribution guidelines (CONTRIBUTING.md)
- Implementations list (IMPLEMENTATIONS.md)
- Taxonomy in CSV and JSON formats

### Taxonomy Notes — v1.0

**Numbering logic:** ESS uses a two-digit division prefix that parallels MasterFormat's division structure but shifts groups to create logical separation between facility construction (10–19), facility services (20–33), site and infrastructure (40–44), and process construction (45–47). The shift also creates reserved expansion space within each group.

**Reserved divisions:** Divisions 15–19, 27–29, 34–39, 48–49 are reserved for future expansion. This is intentional — inserting new work results into reserved space is less disruptive to software implementations than renumbering active content.

**Fire alarm placement:** ESS places fire alarm systems (33 81 13) within the Electrical division rather than as a separate Electronic Safety division. This reflects the reality of how fire alarm systems are specified and coordinated on most commercial projects. This is a deliberate departure from MasterFormat's Division 28 structure and may be revisited in a future major revision based on community feedback.

**Fireproofing placement:** Applied fireproofing is placed in Special Construction (26 33) in ESS, reflecting its special-inspection and third-party oversight requirements. MasterFormat places it in Thermal and Moisture Protection (07 81). Both are defensible; ESS's placement is a considered editorial choice subject to community review.

**Transportation infrastructure:** ESS Division 44 (Transportation) is intentionally broader than MasterFormat's Division 34, which is narrowly focused on rail. ESS 44 covers roadways, bridges, tunnels, and airfield paving as well as rail trackwork, reflecting the full scope of site transportation infrastructure encountered on large commercial and institutional projects.

---

## Upcoming

### [1.1] — Planned
- Incorporate public review comments received during the v1.0 comment period
- Add additional sections based on community proposals meeting the criteria in CONTRIBUTING.md
- Submit taxonomy to buildingSMART Data Dictionary (bSDD)
