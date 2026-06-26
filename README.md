# orinth-1.0-35b tool-eval-bench hardmode run

This directory contains the cross-trial benchmark report and the interactive dashboard for:

- `orinth-1.0-35b_tool-eval-bench_seed-42_trials-8_hardmode.md`
- `orinth-1.0-35b_tool-eval-bench_seed-42_trials-8_hardmode.html`

## What is here

| File | Purpose |
|---|---|
| [`orinth-1.0-35b_tool-eval-bench_seed-42_trials-8_hardmode.md`](./orinth-1.0-35b_tool-eval-bench_seed-42_trials-8_hardmode.md) | Cross-trial summary in Markdown, including scores, reliability metrics, scenario tables, and failure analysis. |
| [`orinth-1.0-35b_tool-eval-bench_seed-42_trials-8_hardmode.html`](./orinth-1.0-35b_tool-eval-bench_seed-42_trials-8_hardmode.html) | Interactive HTML dashboard for browsing the same benchmark results in a browser. |

## Benchmark snapshot

- Model: `ornith-1.0-35b-Q8_0.gguf`
- Backend: `vllm`
- Seed: `42`
- Trials: `8`
- Mode: `hardmode`
- Mean final score: `88.8 ± 0.7`
- Deployability: `78 / 100`
- Reliability gap: `11.9pp`

## Notable outcomes

- Strong and stable performance on most scenarios.
- The main reliability weaknesses are concentrated in a small set of flaky or consistently partial scenarios.
- The Markdown report is the canonical source for the full tabular breakdown.

## Open the dashboard

Open [`orinth-1.0-35b_tool-eval-bench_seed-42_trials-8_hardmode.html`](./orinth-1.0-35b_tool-eval-bench_seed-42_trials-8_hardmode.html) in a browser to inspect the results interactively.
