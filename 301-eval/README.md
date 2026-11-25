# Issue 301 evidence: scoped reading font scaling

Same seeded demo thread at 1440x900 and 390x844. `zoom-*` applies CSS `zoom` to the conversation lane and composer. `font-*` changes only reading font/line-height tokens. All shells remain at the 16px root.

| file | prototype | level | width |
| --- | --- | --- | --- |
| zoom-standard-1440.png | CSS zoom | standard | 1440 |
| zoom-comfortable-1440.png | CSS zoom | comfortable | 1440 |
| zoom-large-1440.png | CSS zoom | large | 1440 |
| font-standard-1440.png | font/line-height tokens | standard | 1440 |
| font-comfortable-1440.png | font/line-height tokens | comfortable | 1440 |
| font-large-1440.png | font/line-height tokens | large | 1440 |
| zoom-standard-390.png | CSS zoom | standard | 390 |
| zoom-comfortable-390.png | CSS zoom | comfortable | 390 |
| zoom-large-390.png | CSS zoom | large | 390 |
| font-standard-390.png | font/line-height tokens | standard | 390 |
| font-comfortable-390.png | font/line-height tokens | comfortable | 390 |
| font-large-390.png | font/line-height tokens | large | 390 |

Companion data:

- `dom-summary.json`: measured computed sizes, widths, overflow flags and fold row geometry for the same 12 states.
- `streaming-results.json`: identical replay-turn streaming metrics for zoom and font at 1440x900.
