# Upload-package changes — 22 October 2026

1. Aymen Ochi explicitly identified as software author/maintainer/copyright holder; human contributions documented, tool assistance separate.
2. MIT licence added with the author's express permission; original OULAD CC BY 4.0 attribution retained separately. Software authorship is distinct from tool assistance.
3. README, software citation, upload instructions and validation scope prepared for a public repository. No public URL, DOI, journal acceptance or institutional ethics exemption invented.
4. The data downloader now enforces the supplied raw SHA256 manifest before writing acquisition metadata; it cannot silently rebaseline corrupt existing CSVs. The original manifest remains unchanged, with execution metadata written separately. Added regression tests exercise a valid tiny archive and a modified existing CSV, without network access.
5. Numerical model code, configurations, result tables, frozen reference tables and split membership are unchanged. Historical source-copy hashes and training reports remain dated evidence; the changed downloader/docs are distinguished from those original files.
6. Raw bulk, local Git metadata/history, caches, third-party PDFs, compiler binaries and manuscript sources are excluded. The archive is ready for author upload, not already published.
