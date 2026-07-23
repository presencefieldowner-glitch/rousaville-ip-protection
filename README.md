# Rousaville IP Protection

Private provenance archive for Rounsaville Technologies intellectual-property records.

## Contents

### R-CoreX Master Dossier

- [`00-IP-REGISTRY/RT-IP-RCOREX-MASTER-001_v1.0.0.md`](00-IP-REGISTRY/RT-IP-RCOREX-MASTER-001_v1.0.0.md) / [`.pdf`](00-IP-REGISTRY/RT-IP-RCOREX-MASTER-001_v1.0.0.pdf) — initial master dossier. Its Section 16 code-to-concept mapping was a placeholder (paths like `/core/`, `/bus/` not yet tied to any repository).
- [`00-IP-REGISTRY/RT-IP-RCOREX-MASTER-001_v1.1.0.md`](00-IP-REGISTRY/RT-IP-RCOREX-MASTER-001_v1.1.0.md) / [`.pdf`](00-IP-REGISTRY/RT-IP-RCOREX-MASTER-001_v1.1.0.pdf) — **current version.** Reconceptualized against the real, git-verified Rounsaville Technologies repositories: Section 16 now cites real file paths and honest implementation status (Implemented / Prototype / Planned / No Corresponding Code) instead of placeholders. See its Version History table for the full diff summary.

### Supporting evidence

- [`00-IP-REGISTRY/RT-IP-RCOREX-MAPPING-002_v1.0.0.md`](00-IP-REGISTRY/RT-IP-RCOREX-MAPPING-002_v1.0.0.md) / [`.pdf`](00-IP-REGISTRY/RT-IP-RCOREX-MAPPING-002_v1.0.0.pdf) — companion record documenting exactly how each R-CoreX concept was mapped to real code, with the repositories surveyed, evidence cited (file paths, docstrings), and the gaps found (e.g. `rounsaville-ai-music-generator` is an empty repository; `presence-resonance` is a separate sibling product with no real R-CoreX implementation).

Every `.pdf` and `.md` file has a matching `.sha256` checksum, computed at commit time, for tamper-evidence.

### Repository structure (dossier Section 24)

The numbered folders below implement `RT-IP-RCOREX-MASTER-001` Section 24's "Recommended Master Repository Structure." Each one is a real index into `presencefieldowner-glitch/RealityStateOS`'s actual implementation (not a placeholder) — see `00-IP-REGISTRY/RT-IP-RCOREX-MAPPING-002_v1.0.0.md` for the full evidence behind every cross-reference.

| Folder | Real content |
|---|---|
| [`00-IP-REGISTRY/`](00-IP-REGISTRY/) | The dossier + mapping record, `asset-index.csv`, `ownership-records/` |
| [`01-R-COREX/`](01-R-COREX/) | Architecture/specifications/diagrams — all point to `RealityStateOS`'s real module map and RFCs |
| [`02-NINE-PHASE-PIPELINE/`](02-NINE-PHASE-PIPELINE/) | Per-phase index into LakeTiticaca's real 5-step cognition loop |
| [`03-VERIFIED-BUS/`](03-VERIFIED-BUS/) | Points to `004_VERIFIED_BUS/` |
| [`04-IHI/`](04-IHI/) | Honest "no dedicated module" note |
| [`05-RHI/`](05-RHI/) | Points to `reasoning.py`/`inference.py` and `009_INTELLIGENCE/` |
| [`06-NHI/`](06-NHI/) | Points to `011_INTERFACE/`'s real REST+CLI |
| [`07-SRI/`](07-SRI/) | Points to `008_REALITY_TAPE/`, notes hardware-intake scope |
| [`08-TELEMETRY/`](08-TELEMETRY/) | Schemas/identity/provenance/verification/audit, each with real paths |
| [`09-APIS/`](09-APIS/) | Points to `plugins.py` |
| [`10-THIRD-PARTY-LICENSES/`](10-THIRD-PARTY-LICENSES/) | Real dependency table (typescript, @noble/*, ulid, smol-toml, cryptography, ...) |
| [`11-CONTRIBUTORS/`](11-CONTRIBUTORS/) | Current sole contributor + policy pointer |
| [`12-RELEASES/`](12-RELEASES/) | Version history of this repo's documents and of `RealityStateOS`'s module build-out |
| [`13-LEGAL/`](13-LEGAL/) | Pointers into the dossier's legal-limitations sections |

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
