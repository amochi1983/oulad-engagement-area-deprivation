# Upload-package validation — 22 October 2026

## Checks actually executed

A fresh isolated copy of the portable repository was created with no raw CSVs or raw archive. `python reproduce.py --download` completed successfully (exit 0) using the existing Python 3.12 scientific environment on Windows. It downloaded the official version-1 archive, checked the source bytes, restored the seven CSVs, and ran **19 tests: 19 passed**, with three existing dependency pending-deprecation warnings.

The shipped manifest was unchanged after acquisition. All eight expected raw hashes (archive plus seven CSVs) matched. Two new acquisition regression tests use tiny local fixtures: valid acquisition preserves the expected manifest, while a modified existing CSV raises an error without overwriting that manifest.

All original scientific Python ASTs are unchanged after adding Aymen Ochi author/licence comments, except the documented download-provenance guard. The numerical tables, processed cohorts, selected model/prediction artefacts, configuration, frozen references and split assignments are byte-identical to the existing validated scientific copy.

Legacy Markdown table text is unchanged; its line endings were normalised to LF for portable Git checkouts. Every Python source has an Aymen Ochi author header and MIT SPDX identifier. Citation and licence metadata identify Aymen Ochi as software author; tool assistance is disclosed only in AI_ASSISTANCE.md. No raw bulk, .git history, runtime/cache, publisher PDF, manuscript, compiler or dependency binary is included. Every upload file is below the browser's 25 MiB per-file limit.

## Scope

This run is **fresh acquisition plus integrity/numerical tests**, not a new complete model-training run or fresh dependency installation. The full manuscript-core refitting/retraining evidence remains the dated 18 October audit. No external cohort, causal effect, institutional ethics exemption, journal submission or editorial acceptance is established by these checks. The author's confirmed public-code release permission is distinct from final manuscript approval.

A source/upload manifest and external archive-integrity report identify the delivered snapshot. Generated local files may change after reproduction. The source code and source-data licence scopes are described in LICENSE_STATUS.md and DATA_LICENSE.md.
