# Audit Trails

Kernel-AI-level: `RealityStateOS/002_KERNEL/LakeTiticaca/laketiticaca/version_control.py` (git-lite, append-only).

Module-level: `RealityStateOS/005_KNOWLEDGE/src/versioning.ts` (per-item version history) and `RealityStateOS/999_OPERATIONS/src/auditLog.ts` (retention-pruned audit log, backs `rsos audit log --since`).

Status: implemented, tested.
