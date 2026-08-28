# GitHub Implementations

## vis-nlp/ChartQA
**What it implements:** Official ChartQA dataset release and baseline transformer-based model code for chart question answering.
**Why it's relevant:** The de facto standard benchmark repository for chart-QA research; well-documented, actively cited, and a reference point for nearly every paper in this collection.
**Link:** [github.com/vis-nlp/ChartQA](https://github.com/vis-nlp/ChartQA)

## princeton-nlp/CharXiv
**What it implements:** Official CharXiv benchmark construction code, evaluation harness, and a public model leaderboard.
**Why it's relevant:** Directly quantifies the axis/scale/legend-reading gap between proprietary models and humans on real scientific charts; actively maintained with regular leaderboard updates.
**Link:** [github.com/princeton-nlp/CharXiv](https://github.com/princeton-nlp/CharXiv)

## MuyeHuang/ChartSketcher
**What it implements:** The official ChartSketcher model (NeurIPS 2025) — a multimodal, feedback-driven step-by-step chart-reasoning system built on Qwen2VL-72B, with released model weights.
**Why it's relevant:** A concrete, reproducible mitigation approach for axis-reading errors via visual self-annotation and iterative reflection.
**Link:** [github.com/MuyeHuang/ChartSketcher](https://github.com/MuyeHuang/ChartSketcher)

## wangfen01/ChartInsighter
**What it implements:** Official ChartInsighter code and benchmark dataset for multi-agent, hallucination-reduced time-series chart summary generation.
**Why it's relevant:** Directly targets hallucinated axis/value claims in generated chart summaries using a self-consistency verification step.
**Link:** [github.com/wangfen01/ChartInsighter](https://github.com/wangfen01/ChartInsighter)

## insait-institute/chartAttack
**What it implements:** The official ChartAttack framework and AttackViz dataset for systematically injecting misleading axis/scale manipulations into MLLM-generated charts.
**Why it's relevant:** Provides an adversarial testbed for evaluating how robust MLLM chart interpretation actually is to designed axis/scale attacks, complementing the benchmark-based papers in this collection.
**Link:** [github.com/insait-institute/chartAttack](https://github.com/insait-institute/chartAttack)