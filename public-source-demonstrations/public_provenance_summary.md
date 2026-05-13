# Public Provenance Summary — EWS-v1_10-BLS-Labor-Use-Case

**Example ID:** EWS-v1_10-BLS-Labor-Use-Case
**Dataset Label:** `EWS v1_10 BLS Labor Use Case`
**Analyzed Date Range:** 2025-01-31 to 2025-12-31
**Evidence Package Release:** EWS MVP1.10
**Analytical Engine Baseline:** EWS MVP1.06
**Evidence Package Generated:** 2026-05-12T19:53:58Z

## What Was Run

The Fueled Analytics Early Warning System was applied to dataset `EWS v1_10 BLS Labor Use Case`.
The scan analyzed 24 KPI(s) over a 12-month lookback window
using a monthly cadence (12 total data points analyzed).

## Outcome Summary

| Metric | Value |
|---|---|
| Evaluation Status | evaluated |
| Overall Drift Severity | critical |
| KPIs Evaluated | 24 |
| KPIs Flagged | 17 |
| KPIs Not Flagged | 7 |

Hires | Rate | not_seasonally_adjusted | Total nonfarm | Total US | All areas has drifted down by ~0.5 units (~14.4%) versus baseline (critical drift). Additional drift is visible in Hires | Level - In Thousands | seasonally_adjusted | Total nonfarm | Total US | All areas, Hires | Rate | seasonally_adjusted | Total nonfarm | Total US | All areas, Job openings | Level - In Thousands | seasonally_adjusted | Total nonfarm | Total US | All areas, and 20 additional evaluated metrics.

## Preserved Artifacts (Short Checksums)

- `run_001/canonical_output.json` SHA-256: `0872576121ee0550…`
- `run_001/signal_brief.html` SHA-256: `8f26e606431792ec…`

Full SHA-256 checksums are in `provenance/artifact_checksums.txt`.

## Public-Safe Scope Statement

This evidence package demonstrates EWS technical capability only.

- Drift severity classifications are relative to operator-configured thresholds.
- EWS does not assess business risk, financial impact, causality, or make predictions.
- These artifacts are for static portfolio and governance demonstration only.
- No live data submission or processing occurs when these artifacts are viewed.
