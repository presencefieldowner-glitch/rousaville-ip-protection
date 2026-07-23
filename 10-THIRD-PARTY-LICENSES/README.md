# Third-Party License Register

Real dependencies in use across `presencefieldowner-glitch/RealityStateOS` as of 2026-07-23, per Section 19's template. None of these are, or become, proprietary Rounsaville Technologies IP merely by being imported.

| Dependency | Version | Purpose | License | Copyright Holder |
|---|---|---|---|---|
| `typescript` | ^5.9.3 | Compiler for every TS module | Apache-2.0 | Microsoft Corporation |
| `@types/node` | ^22.0.0 | Node.js type definitions | MIT | Microsoft Corporation / DefinitelyTyped contributors |
| `@noble/ed25519` | ^3.1.0 | Ed25519 signing/verification (CoreTypes crypto) | MIT | Paul Miller |
| `@noble/hashes` | ^2.2.0 | SHA-512, BLAKE3 hashing (CoreTypes crypto) | MIT | Paul Miller |
| `ulid` | ^3.0.2 | ULID identifiers (RFC-0002 §1) | MIT | Alizain Feerasta / contributors |
| `smol-toml` | ^1.7.0 | TOML config parsing (001_BOOTSTRAP) | MIT | Squirrel Chat / contributors |
| `cryptography` | >=42.0 | AES-GCM encryption (LakeTiticaca `encryption.py`) | Apache-2.0 / BSD (dual) | Python Cryptographic Authority |
| Node.js built-ins (`http`, `zlib`, `crypto`) | (runtime) | HTTP server, gzip, misc | Node.js license (MIT-style) | OpenJS Foundation |

## Notes

- No GPL/LGPL/copyleft dependencies are in use as of this record.
- `smol-toml` was selected specifically because `formats.md`/`settings.md` specify TOML as the config file format — it implements real, general TOML, not a hand-rolled subset.
- This table should be regenerated whenever a module's `package.json`/`pyproject.toml` dependencies change — see each module's own `package.json` for the exact resolved version at any point in time (`package-lock.json` is committed per module).
