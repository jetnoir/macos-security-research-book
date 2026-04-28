# macOS Security Research: A Complete Framework

> A complete six-phase methodology for macOS vulnerability research — from PING as the metaphor for asking systems questions through to coordinated disclosure with vendors.
>
> **By [Stuart Paul Thomas](https://stuart-thomas.com).** First Edition · April 2026 · English Law (England & Wales).

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19855016.svg)](https://doi.org/10.5281/zenodo.19855016)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Free download](https://img.shields.io/badge/Free-Download-brightgreen.svg)](https://stuart-thomas.com/book/macos-security-research/)
[![Read TL;DR](https://img.shields.io/badge/Read-5%20min%20TL%3BDR-blue.svg)](https://stuart-thomas.com/macos-security-framework.html)

---

## What this is

A book about **how** you do macOS security research, not just **what** you find. Distilled from 35 years of practice — starting with a Commodore PET in 1987, through a 2001 SANS paper on ICMP crafting, into modern Darwin/XNU vulnerability research.

The book walks through:

- **Why PING matters** — the gap between specification and implementation, and why a 40-year-old tool still teaches you everything
- **A six-phase framework** — *Scope*, *Recon*, *Research Tracks*, *Red-Team*, *Submission*, *Archive*
- **The discipline of evidence** — proof-of-concept development that gets findings taken seriously
- **Writing for vendors** — what the 90-day responsible disclosure timeline is actually like to live through
- **The red-team conversation** — the five questions every review worth attending will ask
- **The macOS security landscape** — the BSD-to-XNU CVE cross-reference technique; where it works and where it doesn't (TCC, MACF, IOKit are Apple-specific territory)
- **Defence in depth** — what each control actually stops, beyond the marketing

It's a methodology book. It does not contain unpatched vulnerabilities or ready-to-use exploits.

---

## Read or download

| Format | File | Size | Best for |
|--------|------|------|----------|
| **HTML** | [`book/macOS_Security_Research_A_Complete_Framework.html`](book/macOS_Security_Research_A_Complete_Framework.html) | ~95 KB | Read in any browser, copy-paste of code blocks |
| **EPUB** | [`book/macOS_Security_Research_A_Complete_Framework.epub`](book/macOS_Security_Research_A_Complete_Framework.epub) | ~7.0 MB | Kindle, Apple Books, Calibre, Kobo, e-readers |
| **PDF** | [`book/macOS_Security_Research_A_Complete_Framework.pdf`](book/macOS_Security_Research_A_Complete_Framework.pdf) | ~6.2 MB | Printing, page-precise citation, archival |

Companion materials:

- **[5-minute TL;DR](tldr-macos-security-research.html)** — the framework distilled for quick reading
- **[Glossary](glossary.html)** — searchable companion of terms used in the book

The canonical home is at **<https://stuart-thomas.com/book/macos-security-research/>** — this repository mirrors the same files.

---

## Licence

**[Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)**

You are free to:

- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:

- **Attribution** — you must give appropriate credit to *Stuart Paul Thomas*, provide a link to the licence, and indicate if changes were made
- **ShareAlike** — if you remix, transform, or build upon the material, you must distribute your contributions under the [same licence](https://creativecommons.org/licenses/by-sa/4.0/) as the original

The full legal code is in [`LICENSE`](LICENSE) and at <https://creativecommons.org/licenses/by-sa/4.0/legalcode>.

This is a true **copyleft** licence — derivatives must remain free and openly licensed under the same terms. The book is, and will always be, free.

---

## How this book was made

The author is neurodivergent (autism, ADHD).

**Claude (Anthropic)**, **Gemini (Google)**, and **Grok (xAI)** were used as **assistive technology** during preparation: drafting, proofreading, structural editing, formatting of code blocks and citations, and red-team review of arguments.

The underlying research, methodology, opinions, code, and findings are entirely the work of Stuart Paul Thomas. The author is solely responsible for the content.

The use of AI assistive technology is consistent with the principles of the **Equality Act 2010**:

- Disability is defined as a protected characteristic under **Section 6**
- Reasonable adjustments are contemplated by **Sections 20–21**
- Discrimination arising from disability is addressed by **Section 15**

This acknowledgement is provided in the spirit of transparent and accessible research practice.

---

## Found a bug in the book?

> Finding a bug in a book about finding bugs is, the author has to admit, a deeply appropriate thing to do. The author is not above his own methodology. He is, in fact, a test case for it.

Please [open an issue](../../issues) with:

- The chapter or section where the issue lives
- The specific text or claim that needs correction
- (For factual errors) supporting evidence
- (For code that doesn't work) reproduction details

There is no 90-day embargo on errata. Turnaround should be considerably faster.

Email is also fine: **stuartpaulthomas@gmail.com** (suggested subject: `Book Bug Report: macOS Security Research`).

---

## About the author

**Stuart Paul Thomas** is an information security professional with 35+ years of experience in systems engineering, network security, cryptography, and security research. His career spans roles in government, financial services, transportation, telecommunications, and technology sectors.

He started in computing at age 11, in 1987, when he fixed a retired teacher's Commodore PET and its printer. The fee was £5. His first professional IT role was at University College Scarborough in 1994. He has not stopped since.

Other work:

- **Personal site:** <https://stuart-thomas.com>
- **Security research papers:** <https://github.com/jetnoir/security-research> — including the [TriageForge spectral binary screening paper](https://github.com/jetnoir/security-research/blob/main/triageforge-2026.md), [SQL Injection 2026 edition](https://github.com/jetnoir/security-research/blob/main/sql-injection-2026.md), and [ICMP Crafting 2026 edition](https://github.com/jetnoir/security-research/blob/main/icmp-tunneling-2026.md)
- **Whitby Jet provenance platform:** <https://authenticwhitbyjet.co.uk>
- **NTAG 424 DNA SDK for macOS:** <https://github.com/jetnoir/ntag424-macos>

---

## How to cite

The book is archived on [Zenodo](https://zenodo.org/records/19855016) with a permanent DOI: **[10.5281/zenodo.19855016](https://doi.org/10.5281/zenodo.19855016)**.

### APA

> Thomas, S. P. (2026). *macOS Security Research: A Complete Framework* (Version 1.0.0) [Book]. Zenodo. https://doi.org/10.5281/zenodo.19855016

### BibTeX

```bibtex
@book{thomas_2026_macos_security_research,
  author       = {Thomas, Stuart Paul},
  title        = {{macOS Security Research: A Complete Framework}},
  edition      = {First Edition},
  year         = {2026},
  month        = apr,
  publisher    = {Zenodo},
  version      = {1.0.0},
  doi          = {10.5281/zenodo.19855016},
  url          = {https://doi.org/10.5281/zenodo.19855016}
}
```

### Plain text

> Stuart Paul Thomas. (2026). *macOS Security Research: A Complete Framework* (First Edition). DOI: 10.5281/zenodo.19855016.

---

## Repository structure

```
.
├── README.md                              this file
├── LICENSE                                CC BY-SA 4.0 full legal code
├── tldr-macos-security-research.html      5-minute summary
├── glossary.html                          searchable glossary
├── book/
│   ├── macOS_Security_Research_A_Complete_Framework.html
│   ├── macOS_Security_Research_A_Complete_Framework.epub
│   └── macOS_Security_Research_A_Complete_Framework.pdf
└── assets/
    ├── code_audit.png                     illustration for Chapter 4
    ├── coordination.svg                   90-day disclosure timeline
    ├── researcher_examining.png           illustration for Chapter 1
    └── six_phases.svg                     framework diagram
```

The HTML book references the assets via `../assets/` — keep the directory structure intact when forking or mirroring.

---

## Legal notice

This book is provided for educational purposes only. Proof-of-concept code is published for educational and defensive security purposes only. Use only on systems you own, control, or have explicit written authorisation to test. Unauthorised use may constitute a criminal offence under the **Computer Misuse Act 1990** or equivalent legislation in your jurisdiction.

The author retains moral rights under the **Copyright, Designs and Patents Act 1988**.

This book is not legal advice. For legal interpretation of the CMA 1990, Data Protection Act 2018, UK GDPR, or other regulations, consult a qualified solicitor.

---

*© 2026 Stuart Paul Thomas · CC BY-SA 4.0*
