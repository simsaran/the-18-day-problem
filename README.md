# the-18-day-problem
### NorthStar Insurance: Claims Resolution Process DMAIC Analysis
DMAIC process improvement analysis reducing insurance claims resolution time from 18.3 to 9.1 days. Full artifact set: process maps, Pareto analysis, fishbone, 5 Whys, improvement backlog, DMAIC report.

---

## Project overview

NorthStar Insurance (fictional) processes 1,400 claims per month across Auto and Home lines. Average resolution time: **18.3 days**. Industry benchmark: **9 days**. NPS had fallen 14 points over 18 months. Adjuster overtime costs had risen 22% year-over-year.

No one had ever mapped the process end to end. No root cause analysis had ever been conducted.

I ran a full DMAIC Define through Control producing every artifact by hand using web-based tools. The result: a projected reduction from 18.3 days to **9.1 days (50% improvement)** through 5 targeted initiatives requiring zero additional headcount.

---

## The three root causes (Pareto + 5 Whys)

| # | Root Cause | Delay Source | % of Avoidable Delay |
|---|-----------|--------------|----------------------|
| 1 | No claim-type-specific document checklist customers receive a generic email and don't know what to submit | Document Wait | 50.4% |
| 2 | No document completeness validation in claims system 38% of claims loop back for a second request | Rework Loop | 20.9% |
| 3 | Senior review threshold is value-only ($10K) 45% of claims reviewed regardless of complexity | Senior Review Bottleneck | 12.3% |

**3 root causes account for 83.6% of all avoidable delay.**

---

## Key numbers

| Metric | Current State | Future State |
|--------|--------------|--------------|
| Avg resolution time | 18.3 days | 9.1 days |
| Rework loop rate | 38% | < 8% |
| Process steps | 14 | 11 |
| Manual handoffs | 4 | 0 |
| Senior review rate | ~45% of claims | ~20% of claims |
| Value-add time | 30.6% of cycle | 69.4% of cycle |
| Estimated annual overtime saving | — | $423,000 |

---

## DMAIC artifacts

| Phase | Artifact | File |
|-------|----------|------|
| Define | Project Charter | `/define/project-charter.pdf` |
| Define | SIPOC Diagram | `/define/sipoc-diagram.png` |
| Measure | Current State Process Map (14 steps, 4 swim lanes) | `/measure/process-map-current-state.png` |
| Measure | Claims Dataset 300 records | `/measure/claims-dataset.csv` |
| Measure | Process Time Summary | `/measure/process-time-summary.csv` |
| Analyze | Pareto Analysis (Excel workbook + chart) | `/analyze/pareto-analysis.xlsx` |
| Analyze | Fishbone Diagram (6 cause categories) | `/analyze/fishbone-root-cause.png` |
| Analyze | 5 Whys Analysis 3 complete chains | `/analyze/5-whys-analysis.pdf` |
| Improve | Future State Process Map (11 steps) | `/improve/process-map-future-state.png` |
| Improve | Improvement Backlog (12 initiatives, 3 waves) | `/improve/improvement-backlog.xlsx` |
| Control | Full DMAIC Report | `/control/dmaic-report-northstar.pdf` |

---

## Tools used

| Tool | Purpose |
|------|---------|
| Miro | Process maps (current + future state), SIPOC, Fishbone diagram |
| Google Sheets | Claims dataset, Pareto analysis, Process time summary |
| Google Docs | Project charter, 5 Whys analysis, DMAIC report |
| Excel (openpyxl) | Pareto workbook with chart, Improvement backlog |
| Python (Google Colab) | Claims dataset generation, statistical calculations |
| GitHub | Version control, portfolio hosting |

---

## Skills demonstrated

`DMAIC methodology` · `Value stream analysis` · `Pareto analysis (80/20)` · `Root cause analysis` · `5 Whys` · `Ishikawa / Fishbone` · `Process mapping (current + future state)` · `Swim-lane diagrams` · `MoSCoW prioritisation` · `Control planning` · `Business report writing` · `Data analysis` · `Process improvement` · `Stakeholder communication`

---

## How to navigate this repo

```
the-18-day-problem/
├── README.md
├── define/
│   ├── project-charter.pdf
│   └── sipoc-diagram.png
├── measure/
│   ├── process-map-current-state.png
│   ├── claims-dataset.csv
│   └── process-time-summary.csv
├── analyze/
│   ├── pareto-analysis.xlsx
│   ├── fishbone-root-cause.png
│   └── 5-whys-analysis.pdf
├── improve/
│   ├── process-map-future-state.png
│   └── improvement-backlog.xlsx
└── control/
    └── dmaic-report-northstar.pdf
```

---

## About this project

This is Day 1 of Proof in Progress, a 7 day portfolio series where each day I build one practical business case study across process improvement, business analysis, operations, regulatory affairs, digital marketing, and data analysis.

The idea behind this series is simple: instead of only applying to roles and waiting for responses, I’m turning my job search into proof of work.

Each project is built by hand, framed like a real workplace or consulting engagement, and documented with the types of artifacts a professional team would actually produce, including process maps, dashboards, root cause analysis, recommendation memos, trackers, and control plans.

My goal is to show how I think, how I solve problems, and how I translate business issues into structured, practical deliverables.

Prepared by: Simran Saran
Series: Proof in Progress
Day 1 Project: The 18 Day Problem
Target roles: Process Improvement Analyst · Business Analyst · Operations Analyst

---

*NorthStar Insurance is a fictional company created for portfolio purposes. All data is synthetic.*
