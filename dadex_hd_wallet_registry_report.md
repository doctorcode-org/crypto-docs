# Dadex HD Wallet Registry Hardening Report

- Date (UTC): 2026-03-29 12:58:22
- Total SLIP-0044 rows processed: 1321
- Total entries in final registry: 1321
- Validation result: PASS

## Counts
- Count by lifecycle status: {'Active': 1291, 'Unsupported': 12, 'ProtocolOnly': 15, 'Dead': 2, 'Deprecated': 1}
- Count by binding kind: {'Primary': 1318, 'Legacy': 3}
- Count by confidence: {'Official': 1292, 'ProjectPolicy': 29}
- Number of entries with official docs: 181
- Number of entries still inferred: 0
- Number of entries still unresolved: 1140

## Top categories of remaining ambiguity
- references.officialDocs: 1140

## Notable fixes made to the existing bootstrap file
- Normalized all entries to canonical SLIP-0044 coinType/displayName/symbol baseline (with policy placeholders only where SLIP symbol is blank).
- Collapsed binding posture to one entry per coinType and promoted confidence from Inferred to Official/ProjectPolicy as applicable.
- Added canonical SLIP-0044 spec reference across all entries and kept Trust Wallet as enrichment-only source.
- Upgraded Namecoin references with official FAQ documentation.
- Generated conflict and unresolved inventories for explicit follow-up.
