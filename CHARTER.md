# ESS Founding Charter

**Elemental Specification System — Version 1.0**  
*An Open, Copyright-Free Construction Work-Results Taxonomy for North American Practice*

Originated by Eric Letbetter, AIA, CCS, SCIP — Letbetter Ink  
June 2026

---

## 1. Purpose and Intent

The Elemental Specification System (ESS) is an open, copyright-free classification taxonomy for organizing construction work results in North American project manuals, cost models, and building information workflows. It is designed to serve architects, specifiers, engineers, contractors, estimators, owners, and software developers without restriction, fee, or licensing encumbrance.

ESS is not a specification platform, a software product, or a proprietary standard. It is a numbered taxonomy — a structured list of work-result titles and section identifiers — that any person, firm, or software system may use, reproduce, modify, extend, or implement freely, subject only to the terms of the Open Database License (ODbL 1.0) described in Section 5 of this Charter.

> *"The taxonomy of construction belongs to the construction community."*
>
> ESS exists to restore that principle in North American practice.

---

## 2. The Problem This Addresses

The North American construction industry has relied on a single licensed taxonomy — MasterFormat® — as the organizational spine of project manuals, cost codes, and specification software for over six decades. That taxonomy is a joint copyright of the Construction Specifications Institute (CSI) and Construction Specifications Canada (CSC), governed by an end-user license agreement (EULA) that restricts reproduction, derivative works, and software integration.

As of 2026, several conditions have converged to make a free alternative both necessary and viable:

- Software vendors building specification, cost modeling, and BIM platforms pay licensing fees for the right to implement MasterFormat section numbers — costs that are ultimately passed to practitioners and owners.

- AI-assisted specification authorship is emerging as a standard practice. AI tools cannot freely reproduce or derive from licensed taxonomies, creating legal and operational friction at the point of greatest potential productivity gain.

- CSI's membership has declined significantly from its peak, raising questions about the long-term institutional stewardship of a taxonomy the entire industry depends upon.

- No open, copyright-free, North American work-results taxonomy currently exists. The gap is real, documented, and unaddressed by any public project.

ESS is the direct response to that gap.

---

## 3. Design Principles

ESS is built on five non-negotiable design principles. These principles are not aspirational — they are structural. Any version of ESS that departs from them is not ESS.

| Principle | What It Means in Practice |
|---|---|
| **Open** | The taxonomy is published under ODbL 1.0. Any person or entity may use it, implement it, or build upon it without a license, fee, or permission request. |
| **Copyright-Free** | No copyright claim attaches to the section numbers, titles, or organizational structure of ESS. Numbers and titles in a classification taxonomy do not meet the threshold for copyright protection under *Feist v. Rural Telephone*, 499 U.S. 340 (1991). |
| **Work-Results Organized** | ESS organizes information by what is being constructed, not by who constructs it or what phase of a project is underway. This preserves compatibility with existing North American project manual practice. |
| **Self-Maintaining** | Where possible, ESS uses relational structure rather than fixed values requiring manual chasing across editions. The taxonomy is designed to be stable between major revisions. |
| **Community-Governed** | No single entity — individual, firm, or corporate sponsor — controls ESS. Versioning, amendments, and governance are subject to a community process defined in Section 6. |

---

## 4. What ESS Is and Is Not

**ESS IS:**
- A numbered classification taxonomy
- A freely licensed community resource
- Organized by work results
- Available for software integration without fee
- Designed for North American practice
- Open to community extension and amendment

**ESS IS NOT:**
- A specification writing platform
- A CSI or CSC product or derivative
- A product database or manufacturer catalog
- Proprietary to any firm, sponsor, or platform
- A replacement for SectionFormat or PageFormat
- Subject to copyright by any contributor

---

## 5. Licensing

ESS is released under the **Open Database License (ODbL) version 1.0**, published by the Open Data Commons project.

Full license text: https://opendatacommons.org/licenses/odbl/1-0/

The ODbL was chosen because:

1. It is purpose-built for structured data and databases, making it more appropriate for a classification taxonomy than a literary copyright license.

2. It includes a **ShareAlike provision**: any database derived from ESS must be released under equivalent open terms, preventing a private entity from incorporating ESS into a proprietary taxonomy and closing it off from the community.

3. It is **attribution-based**: implementations and derivatives must credit ESS and make the open database accessible alongside any closed layers built on top of it.

4. It is recognized and understood by the open data and open source software communities, easing software integration.

### The Anti-Capture Mechanism

The ODbL ShareAlike provision is ESS's structural anti-capture mechanism.

Any derivative taxonomy must remain open. Any software that embeds ESS and produces a modified version of the taxonomy must release that modification under equivalent terms. No firm, sponsor, or platform may privatize what the community builds.

### Contributor License

Contributors to ESS — whether adding section titles, correcting errors, or proposing new divisions — irrevocably dedicate their contributions to the public domain or, where that is not legally available, license their contributions under ODbL. No contributor retains copyright in any portion of the taxonomy.

---

## 6. Governance

ESS is governed as a community resource. The following principles define its governance structure at founding.

### 6.1 Stewardship Council

ESS is overseen by a Stewardship Council of no fewer than three and no more than nine individuals, each of whom must be a practicing construction industry professional (architect, specifier, engineer, contractor, cost estimator, or software developer serving the industry). Council members serve two-year terms with staggered rotation. No single employer, firm, or corporate sponsor may hold more than one seat.

### 6.2 Founding Stewards

The founding stewards are identified in the ESS repository as of initial publication. Additional co-stewards may be nominated by the founding stewards and accepted by consensus within the first 12 months of publication.

### 6.3 Versioning

ESS uses a two-tier versioning model:

- **Minor revisions** (new section titles, corrections, editorial clarifications) are published as point releases (e.g., ESS 1.1) and require approval of a simple majority of the Stewardship Council.

- **Major structural revisions** (renumbering, division additions or deletions, changes to organizational logic) require a 60-day public comment period followed by a two-thirds supermajority of the Council.

### 6.4 Sponsor Relationships

Corporate sponsors and implementation partners are welcome and valued. Their contributions of funding, R&D, and advocacy are acknowledged publicly. However, sponsors have no vote in governance, no veto over versioning decisions, and no ownership interest in the taxonomy. Sponsorship is a recognition of support, not a grant of authority.

### 6.5 Anti-Capture Clause

No entity — individual, corporate sponsor, or institutional partner — may acquire, assert, or attempt to assert any proprietary right in ESS or any version of it. Any attempt to do so is grounds for immediate removal from any advisory or sponsor relationship with the project. The Stewardship Council is obligated to publicly disclose and resist any such attempt.

---

## 7. Implementation Partners

ESS is designed for implementation. Software vendors, specification platforms, cost modeling systems, and BIM tools are explicitly invited to implement ESS without fee or permission. Implementation is the point.

An implementation partner is any firm or individual that builds software, tooling, templates, or workflows on top of ESS and publicly acknowledges that implementation. Implementation partners are encouraged but not required to:

- Contribute bug reports and proposed corrections to the taxonomy through the public repository
- Participate in the public comment process for major revisions
- Identify themselves publicly as ESS implementations, enabling the community to locate conforming tools

No implementation partner acquires governance rights or any ownership interest in ESS through their implementation, regardless of the scale of their contribution to the ecosystem.

---

## 8. Repository and Publication

ESS is published in a public GitHub repository under the Letbetter Ink organization. The repository contains:

- The complete ESS taxonomy in machine-readable formats (CSV, JSON, and plain text)
- This Charter document
- A MasterFormat cross-reference mapping (advisory, not normative)
- Contribution guidelines and the public comment process
- A version history and change log
- An implementations list

The taxonomy is also submitted to the buildingSMART Data Dictionary (bSDD) as a freely accessible public classification system, enabling integration with IFC-based BIM workflows without additional licensing.

---

## 9. A Note on MasterFormat

ESS is not an attack on the Construction Specifications Institute, its members, or the decades of professional work invested in MasterFormat. MasterFormat is a product of genuine expertise and has served the industry well. The concern ESS addresses is structural, not personal: a single licensed taxonomy with no open alternative creates a fragile dependency that the industry did not choose consciously and has not had the option to change.

ESS is that option. It competes on merit, not grievance. If MasterFormat becomes open and freely licensed, ESS will have succeeded in its purpose whether or not it survives as a distinct taxonomy.

---

## Founding Steward Signature

**Eric Letbetter, AIA, CCS, SCIP**  
Founding Steward, Elemental Specification System  
Letbetter Ink — Alpharetta, Georgia  
June 2026
