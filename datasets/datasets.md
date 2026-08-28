# Datasets

## ChartQA
**Source:** Masry, Long, Tan, Joty, Hoque (2022), Findings of ACL
**Description:** Human-authored and machine-generated question-answer pairs (9.6K + 23.1K) over real-world charts crawled from Statista, Pew Research, Our World in Data, and OECD.
**Application:** Standard benchmark for evaluating chart-QA visual and logical reasoning, including axis-based value retrieval.
**Link:** [GitHub — vis-nlp/ChartQA](https://github.com/vis-nlp/ChartQA)

## PlotQA
**Source:** Methani, Ganguly, Khapra, Kumar (2020), WACV
**Description:** 28.9 million question-answer pairs over 224,377 real-world scientific plots (bar, line, dot-line), with real-valued (not fixed-vocabulary) answers.
**Application:** Directly tests whether a model can extract precise numeric values by reading axis scales, rather than selecting from a small answer set.
**Link:** [GitHub — NiteshMethani/PlotQA](https://github.com/NiteshMethani/PlotQA)

## CharXiv
**Source:** Wang, Xia, He, Chen, Liu, Zhu, Liang, Wu, Liu, Malladi, Chevalier, Arora, Chen (2024), NeurIPS
**Description:** 2,323 real, unedited charts hand-picked from scientific papers on arXiv across 8 major subjects, with descriptive and reasoning question types.
**Application:** Realistic stress test showing a 33-point gap between top proprietary models (GPT-4o, 47.1%) and human performance (80.5%), much of it attributable to structural element misreading (axes, legends, units).
**Link:** [GitHub — princeton-nlp/CharXiv](https://github.com/princeton-nlp/CharXiv)

## ChartCap
**Source:** Lim, Ahn, Kim (2025), arXiv
**Description:** 565K real-world chart images paired with type-specific, dense captions built via a four-stage generation pipeline with cycle-consistency-based human verification.
**Application:** Training and evaluating hallucination-free, structurally grounded chart captioning (including correct axis/unit description).
**Link:** [Project Page](https://junyoung-00.github.io/ChartCap/)

## ChartQAPro
**Source:** Masry et al. (2025), Findings of ACL
**Description:** 1,948 questions over 1,341 charts from 157 diverse sources, including infographics and dashboards, spanning multiple-choice, conversational, hypothetical, and unanswerable question types.
**Application:** Stress-tests axis/scale robustness under messier, more realistic real-world chart formats than earlier benchmarks.
**Link:** [Hugging Face — ahmed-masry/ChartQAPro](https://huggingface.co/datasets/ahmed-masry/ChartQAPro)