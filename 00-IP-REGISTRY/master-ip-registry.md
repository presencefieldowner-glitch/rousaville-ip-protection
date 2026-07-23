# Master IP Registry (Working Index)

This is the working, evidence-linked index the dossier's Section 24 ("Recommended Master Repository Structure") describes. It is generated from — and should be kept in sync with — `RT-IP-RCOREX-MASTER-001` Section 13 and the companion mapping record `RT-IP-RCOREX-MAPPING-002`.

See [`asset-index.csv`](asset-index.csv) for the machine-readable table (26 assets as of the last sync).

## How to keep this current

1. When a new module, repository, or file becomes the real implementation of a dossier concept, add or update its row in `asset-index.csv`.
2. Update the corresponding folder README under this repository's numbered structure (`01-R-COREX/` through `13-LEGAL/`) to point at the new real path.
3. Bump the master dossier's version in the `rousaville-ip-protection` `00-IP-REGISTRY/` folder and record the change in its Version History table.

## Source of truth

- Conceptual architecture + IP framing: `RT-IP-RCOREX-MASTER-001` (this folder).
- Concept-to-code evidence: `RT-IP-RCOREX-MAPPING-002` (this folder).
- Actual implementation: `presencefieldowner-glitch/RealityStateOS`.
