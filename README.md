# Project Cr0ws — Prometheus

**Created Infinitive Virtual MultiVerse · Born from Prometheus 3.**
The living codebase brain of the Tokyube VoxelVerse engine.
Cr0ws is the codename for Tokyube. Project Scorch remains the VR twin.

One self-contained `index.html` — React 18 + a purged Tailwind utility layer, a 3D particle
brain (three.js), binary matrix rain, and the complete engine inventory: every file, all REST
routes, all codeblocks, all components, cloud schema, save folders, and the Vault
(repos · branches · Steam pipeline).

## Access

The entire site is **AES-256-GCM encrypted** (PBKDF2, 250k iterations). It is ciphertext until
the key is entered — view-source reveals nothing.

- The key is **not** in this repo. Locally it sleeps in `encryptedWaffle.txt` (gitignored, never committed).
- Unlock persists for the browser session.

## Deploy to GitHub Pages

Push `index.html` + `.nojekyll` to `main` (repo root), enable Pages from `main` / root.
Live at: `https://tokyubevoxelverse.github.io/Proj3ctCr0ws/`

To change content or the key: edit `src/` (gitignored — **never push it**, it is the
unencrypted site), then `node src\build.js` regenerates `index.html`.

## Related

- Engine (private): [tokyubevoxelverse/TokyubeVoxelVerse](https://github.com/tokyubevoxelverse/TokyubeVoxelVerse)

---
Compiled read-only from `ChunkWorldGen` — zero files were written into the engine by this site's build.
