# Rousaville IP Protection

Private provenance archive for Rounsaville Technologies intellectual-property records.

## Contents

### R-CoreX Master Dossier

- [`00-IP-REGISTRY/RT-IP-RCOREX-MASTER-001_v1.0.0.md`](00-IP-REGISTRY/RT-IP-RCOREX-MASTER-001_v1.0.0.md) / [`.pdf`](00-IP-REGISTRY/RT-IP-RCOREX-MASTER-001_v1.0.0.pdf) — initial master dossier. Its Section 16 code-to-concept mapping was a placeholder (paths like `/core/`, `/bus/` not yet tied to any repository).
- [`00-IP-REGISTRY/RT-IP-RCOREX-MASTER-001_v1.1.0.md`](00-IP-REGISTRY/RT-IP-RCOREX-MASTER-001_v1.1.0.md) / [`.pdf`](00-IP-REGISTRY/RT-IP-RCOREX-MASTER-001_v1.1.0.pdf) — **current version.** Reconceptualized against the real, git-verified Rounsaville Technologies repositories: Section 16 now cites real file paths and honest implementation status (Implemented / Prototype / Planned / No Corresponding Code) instead of placeholders. See its Version History table for the full diff summary.

### Supporting evidence

- [`00-IP-REGISTRY/RT-IP-RCOREX-MAPPING-002_v1.0.0.md`](00-IP-REGISTRY/RT-IP-RCOREX-MAPPING-002_v1.0.0.md) / [`.pdf`](00-IP-REGISTRY/RT-IP-RCOREX-MAPPING-002_v1.0.0.pdf) — companion record documenting exactly how each R-CoreX concept was mapped to real code, with the repositories surveyed, evidence cited (file paths, docstrings), and the gaps found (e.g. `rounsaville-ai-music-generator` is an empty repository; `presence-resonance` is a separate sibling product with no real R-CoreX implementation).

Every `.pdf` and `.md` file has a matching `.sha256` checksum, computed at commit time, for tamper-evidence.

## Provenance record

| Field | Value |
|---|---|
| Document ID | RT-IP-RCOREX-MASTER-001 (+ companion RT-IP-RCOREX-MAPPING-002) |
| Current Version | 1.1.0 (master) / 1.0.0 (mapping) |
| Organization | Rounsaville Technologies |
| Principal Architect / Author | Joseph Michael Rounsaville |
| Initial Documentation Date | July 22, 2026 |
| Latest Revision Date | July 23, 2026 |
| Classification | Proprietary / Confidential — Internal Master Record |

These documents are technical provenance and IP-management records. They do not by themselves constitute a patent application, trademark registration, copyright registration, or signed IP assignment agreement — see Section 27 ("Legal and IP Limitations") of the master dossier.

## On tagging

Each commit that introduces a new document version is intended to be marked with an annotated git tag (e.g. `RT-IP-RCOREX-MASTER-001-v1.1.0`) to anchor a chronological, hash-verifiable evidence trail in git history alongside the PDF. Tag creation from this automated session is currently blocked by session policy (git relay restricts pushes to `refs/heads/*` only) — tags should be created manually from a normal git client: `git tag -a RT-IP-RCOREX-MASTER-001-v1.1.0 -m "..." <commit> && git push origin RT-IP-RCOREX-MASTER-001-v1.1.0`.
