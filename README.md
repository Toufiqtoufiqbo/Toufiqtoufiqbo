# Hi, I'm Toufik 👋

**Threat intelligence & security tooling.** I work on STIX 2.1 / OpenCTI connectors,
Python automation, and Arabic (RTL) localization of open-source software.

---

## 🛡️ Threat intelligence

Contributed a hardening fix to **[KasperskyLab/threat-intelligence](https://github.com/KasperskyLab/threat-intelligence/pull/4)**:

> A malformed `threat_score=` record in an OpenCTI feed no longer aborts the whole sync run —
> the invalid record is skipped and a sanitized warning is logged instead.

Comfortable across the OpenCTI stack: STIX 2.1 objects, feeds & connectors, `pycti`.

## 🌍 Arabic localization & RTL

Built a complete Arabic patch set for a large open-source web application — **18 files**:

- **Full Arabic translation catalog** — `ar/translation.json` (+2,072 lines) with `README-ar.md`
- **RTL engine** — `rtl.css` plus app-shell and sidebar layout fixes
- **Arabic-aware backend** — text normalization (`arabic_text.py`), Arabic-aware document retrieval, Arabic TTS
- **Hijri calendar** — `hijri.ts` + calendar views
- **Translation tooling** — scripts to generate and merge the catalog

## 🧪 How I work

Findings first, evidence always. Every fix I submit ships with **regression tests** —
the threat-intelligence change above includes 9 tests covering the valid path,
the malformed path, and log sanitization.

## 🧰 Toolbox

`Python` · `STIX 2.1 / OpenCTI` · `pytest` · `Git / GitHub Actions`
`TypeScript / Svelte` · `i18n & RTL engineering` · `Linux`

---

🕵️ Interested in CTF and offensive-security research.
📫 Open to collaboration — reach me through **Issues** or **Discussions** on my repos.
