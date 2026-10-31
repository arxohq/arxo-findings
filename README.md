# Arxo Findings Register

Verified discrepancies in legal texts, standards, official publications and implementations, with evidence and correction histories.

Published by Arxo Law. Human-readable register: https://arxo.io/findings/

This directory is generated from Arxo's finding records; it is never edited by hand.
Build: 2026-10-31T11:45:00+00:00. Records: 253 (201 discrepancies, 52 questions).

## Files

| File | Content |
|---|---|
| `register.json` | all records and counts, format `arxo.public-findings/0.2` |
| `findings.csv` | one row per record, for spreadsheets |
| `findings/<ID>.json` | one record |
| `feed.atom` | new records and changes |
| `index.html`, `<ID>/index.html`, `method/index.html`, `policy/index.html` | the register pages and the disclosure principles |
| `sources/` | copies of the official texts used to check each quotation, named by SHA-256 |
| `SHA256SUMS` | SHA-256 of every file in this build |

## Rules

- A record is published after the finding is confirmed and every responsible institution has been told. Publication does not wait for a reply.
- A record ID (`ARXO-YYYY-NNNN`, year of first publication) is never reused or renumbered. A withdrawn record stays under its ID with the reason.
- "Corrected" requires an official document. A correction published before our report is shown as "Corrected before our report".
- `jurisdiction` is an ISO 3166-1 code (EU for acts of the European Union). A text that no state issued — a standard, an international instrument — carries `issuer` instead, and its `jurisdiction` is null.
- Quotations are verbatim from the official material; translations are ours and marked.
- Counts are of findings. One finding is one independently checkable statement about one discrepancy at one place; classes and questions are counted separately and are not added together.

## Licence

Data: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/), attribution "Arxo Law, Arxo Findings Register". Quoted official texts remain under their own terms.

## Disputes and updates

Objections, reports of our own mistakes and requests for verification: hi@arxo.io — give the record ID, the conclusion you dispute and your source. We acknowledge receipt within five working days and answer on the merits within ten.
Principles: `policy/index.html` (Responsible Disclosure of Defects in Law).
