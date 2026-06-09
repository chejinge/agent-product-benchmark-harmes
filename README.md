# Agent Product Benchmark — Harmes

A structured benchmark suite for evaluating AI agent performance on realistic product-engineering tasks.

## Structure

```
├── README.md
├── rubric/
│   └── scoring.md
├── tasks/
│   ├── task_01_data_analysis.md
│   ├── task_02_bug_fix.md
│   ├── task_03_api_integration.md
│   ├── task_04_report_generation.md
│   └── task_05_code_review.md
├── results/
│   └── summary.md
└── artifacts/
    ├── sales_data.csv
    └── node_project.tar.gz
```

## Tasks Overview

| # | Task | Category | Difficulty |
|---|------|----------|------------|
| 1 | Data Analysis | Analytics | Medium |
| 2 | Bug Fix | Debugging | Easy |
| 3 | API Integration | Engineering | Hard |
| 4 | Report Generation | Documentation | Medium |
| 5 | Code Review | Quality | Medium |

## Quick Start

1. Read `rubric/scoring.md` for evaluation criteria.
2. Pick a task from `tasks/`.
3. Use artifacts in `artifacts/` as input data or project scaffolds.
4. Record results in `results/summary.md`.

## Scoring

See [rubric/scoring.md](rubric/scoring.md) for the full rubric. Each task is scored 0-10 across four dimensions: **Correctness**, **Completeness**, **Clarity**, and **Efficiency**.

## License

MIT
