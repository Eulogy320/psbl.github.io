# PSBL publication audit

Audit status: 27 November 2026

## Scope and result

- `_data/sources.yaml`: 140 source records reviewed; 135 active records (129 papers and 6 books).
- `_data/citations.yaml`: 135 active citation cards synchronized with the source data.
- 32 literal date values changed against the repository `HEAD` metadata; all 140 source records now carry `date_precision` and `date_source` so year-only placeholders are not presented as exact days.
- DOI normalization/deduplication is retained. Five duplicate source records remain marked with `remove: true` and were not deleted.
- 41 Unpaywall candidates had an explicit Creative Commons license and a PDF location. 30 were downloaded and verified with `pdfinfo`; their first pages were rendered as PNG covers.
- 11 candidates remain pending because all attempted legal endpoints returned HTTP 403 or an HTML challenge instead of a verifiable PDF. No paywalled or Sci-Hub material was used.

## Files changed

- `_data/sources.yaml`
- `_data/citations.yaml`
- `_includes/citation.html`
- `papers/`: 30 new PDF files and 30 corresponding first-page PNG files.

The PDF and PNG paths are recorded in both YAML datasets. Every recorded local PDF and image currently exists and all 30 new PDFs pass `pdfinfo` validation.

## Pending OA candidates

These have an explicit CC license in the Unpaywall export but could not be downloaded as a verifiable PDF during this pass:

- `10.1016/j.molp.2019.09.002`
- `10.1016/j.ygeno.2021.12.018`
- `10.1093/bioinformatics/btl496`
- `10.1093/bioinformatics/btw702`
- `10.1093/jxb/erw170`
- `10.1093/plcell/koae038`
- `10.1104/pp.111.183939`
- `10.1105/tpc.112.100669`
- `10.1111/ecog.05100`
- `10.3390/ijms21228472`
- `10.3390/ijms25137245`

## Verification note

YAML parsing and asset-path checks pass. The Jekyll build was not run because the checkout requires Bundler 2.5.6, which is not installed in the current environment. No push was performed.
