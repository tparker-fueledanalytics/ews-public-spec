# Input Reference — EWS-v1_10-BLS-Labor-Use-Case

This document describes the parameters and metadata associated with the evidence
capture. Input data files are not stored in this evidence package.

## Dataset Identifier

**client_id / dataset label:** `EWS v1_10 BLS Labor Use Case`

## Scan Parameters

| Parameter | Value |
|---|---|
| Requested Lookback Window | 12 months |
| Inferred Data Cadence | monthly |
| KPIs Evaluated | 24 |
| KPIs Flagged | 17 |
| KPIs Not Flagged | 7 |
| Recognized KPI Fields | JTS000000000000000HIL, JTS000000000000000HIR, JTS000000000000000JOL, JTS000000000000000JOR, JTS000000000000000LDL, JTS000000000000000LDR, JTS100000000000000HIL, JTS100000000000000HIR, JTS100000000000000JOL, JTS100000000000000JOR, JTS100000000000000LDL, JTS100000000000000LDR, JTU000000000000000HIL, JTU000000000000000HIR, JTU000000000000000JOL, JTU000000000000000JOR, JTU000000000000000LDL, JTU000000000000000LDR, JTU100000000000000HIL, JTU100000000000000HIR, JTU100000000000000JOL, JTU100000000000000JOR, JTU100000000000000LDL, JTU100000000000000LDR |

## Date Coverage

| Range | Value |
|---|---|
| Uploaded Data Range | 2025-01-31 → 2025-12-31 |
| Analyzed Data Range | 2025-01-31 → 2025-12-31 |
| Baseline Window | 8 data points |
| Recent Window | 4 data points |
| Total Points Analyzed | 12 |

## Evaluation Outcome

| Field | Value |
|---|---|
| Evaluation Status | evaluated |
| Overall Drift Severity | critical |
| Overall Message | Hires | Rate | not_seasonally_adjusted | Total nonfarm | Total US | All areas has drifted down by ~0.5 units (~14.4%) versus baseline (critical drift). Additional drift is visible in Hires | Level - In Thousands | seasonally_adjusted | Total nonfarm | Total US | All areas, Hires | Rate | seasonally_adjusted | Total nonfarm | Total US | All areas, Job openings | Level - In Thousands | seasonally_adjusted | Total nonfarm | Total US | All areas, and 20 additional evaluated metrics. |

## Notes

- This reference is for traceability purposes only.
- The canonical JSON (`run_001/canonical_output.json`) is the source of truth for
  all output values. This document restates selected fields only.
- Input data is **not** stored in this evidence package.
- EWS classifies drift severity only. It does not assess business risk, financial
  impact, causality, or make predictions.
