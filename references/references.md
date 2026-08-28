# References

All entries below were independently verified against a primary scholarly source (arXiv abstract page, ACL Anthology, IEEE Xplore, or official conference proceedings) as part of this repository's citation-integrity process. Author lists reflect the verified primary source, not the original AI-generated draft (see `citation-audit/Citation_Integrity_Audit.pdf` for the full correction log).

## Survey Papers

- **Hallucination of Multimodal Large Language Models: A Survey**
  Zechen Bai, Pichao Wang, Tianjun Xiao, Tong He, Zongbo Han, Zheng Zhang, Mike Zheng Shou — arXiv, 2024
  [Paper (arXiv:2404.18930)](https://arxiv.org/abs/2404.18930)
  Comprehensive survey of causes, benchmarks, and mitigation strategies for MLLM hallucination — the umbrella phenomenon that includes axis/scale misreading.

- **Transformers Utilization in Chart Understanding: A Review of Recent Advances & Future Trends**
  Mirna Al-Shetairy, Hanan Hindy, Dina Khattab, Mostafa M. Aref — arXiv, 2024
  [Paper (arXiv:2410.13883)](https://arxiv.org/abs/2410.13883)
  Dedicated review of transformer-based approaches specifically for chart comprehension.

## Foundational Papers

- **ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning**
  Ahmed Masry, Do Xuan Long, Jia Qing Tan, Shafiq Joty, Enamul Hoque — Findings of ACL, 2022
  [Paper (ACL Anthology)](https://aclanthology.org/2022.findings-acl.177/)
  The field's standard chart-QA benchmark; large-scale, human- and machine-generated questions requiring visual and logical reasoning.

- **PlotQA: Reasoning over Scientific Plots**
  Nitesh Methani, Pritha Ganguly, Mitesh M. Khapra, Pratyush Kumar — WACV, 2020
  [Paper (CVF Open Access)](https://openaccess.thecvf.com/content_WACV_2020/html/Methani_PlotQA_Reasoning_over_Scientific_Plots_WACV_2020_paper.html)
  Introduces open-vocabulary, real-valued reasoning over scientific plots at scale (28.9M QA pairs).

- **UniChart: A Universal Vision-Language Pretrained Model for Chart Comprehension and Reasoning**
  Ahmed Masry, Parsa Kavehzadeh, Xuan Long Do, Enamul Hoque, Shafiq Joty — EMNLP, 2023
  [Paper (ACL Anthology)](https://aclanthology.org/2023.emnlp-main.906/)
  Chart-specific low- and high-level pretraining objectives for structural chart-element and reasoning understanding.

## Recent Research Papers

- **CharXiv: Charting Gaps in Realistic Chart Understanding in Multimodal LLMs**
  Zirui Wang, Mengzhou Xia, Luxi He, Howard Chen, Yitao Liu, Richard Zhu, Kaiqu Liang, Xindi Wu, Haotian Liu, Sadhika Malladi, Alexis Chevalier, Sanjeev Arora, Danqi Chen — NeurIPS, 2024
  [Paper (arXiv:2406.18521)](https://arxiv.org/abs/2406.18521)
  Realistic, arXiv-sourced charts reveal a 33-point human/GPT-4o performance gap.

- **ChartX & ChartVLM: A Versatile Benchmark and Foundation Model for Complicated Chart Reasoning**
  Renqiu Xia, Bo Zhang, Hancheng Ye, Xiangchao Yan, Qi Liu, Hongbin Zhou, Zijun Chen, Min Dou, Botian Shi, Junchi Yan, Yu Qiao — arXiv, 2024
  [Paper (arXiv:2402.12185)](https://arxiv.org/abs/2402.12185)
  18 chart types, 22 disciplinary topics; interpretable ChartVLM foundation model.

- **ChartBench: A Benchmark for Complex Visual Reasoning in Charts**
  Zhengzhuo Xu, Sinan Du, Yiyan Qi, Chengjin Xu, Chun Yuan, Jian Guo — arXiv, 2023/2024
  [Paper (arXiv:2312.15915)](https://arxiv.org/abs/2312.15915)
  Deliberately avoids data-point annotations to force genuine axis/legend-based value derivation.

- **ChartInsights: Evaluating Multimodal Large Language Models for Low-Level Chart Question Answering**
  Yifan Wu, Lutao Yan, Leixian Shen, Yunhai Wang, Nan Tang, Yuyu Luo — Findings of EMNLP, 2024
  [Paper (ACL Anthology)](https://aclanthology.org/2024.findings-emnlp.710/)
  19 MLLMs evaluated on low-level tasks (value extraction, correlation ID); 39.8% average accuracy.

- **ChartQAPro: A More Diverse and Challenging Benchmark for Chart Question Answering**
  Ahmed Masry, Mohammed Saidul Islam, Mahir Ahmed, Aayush Bajaj, Firoz Kabir, Aaryaman Kartha, Md Tahmid Rahman Laskar, Mizanur Rahman, Shadikur Rahman, Mehrad Shahmohammadi, Megh Thakkar, Md Rizwan Parvez, Enamul Hoque, Shafiq Joty — Findings of ACL, 2025
  [Paper (ACL Anthology)](https://aclanthology.org/2025.findings-acl.978/)
  Infographics, dashboards, multiple-choice and unanswerable questions for real-world robustness testing.

- **How Good (Or Bad) Are LLMs at Detecting Misleading Visualizations?**
  Leo Yu-Ho Lo, Huamin Qu — arXiv, 2024 / IEEE TVCG, 2025
  [Paper (arXiv:2407.17291)](https://arxiv.org/abs/2407.17291)
  Nine prompting strategies tested against 21 known chart-manipulation issues across four MLLMs.

- **ChartAttack: Testing the Vulnerability of LLMs to Malicious Prompting in Chart Generation**
  Jesus-German Ortiz-Barajas, Jonathan Tonglet, Vivek Gupta, Iryna Gurevych — arXiv, 2026
  [Paper (arXiv:2601.12983)](https://arxiv.org/abs/2601.12983)
  Framework for injecting misleading axis/scale manipulations into MLLM-generated charts; 17–20 point accuracy degradation observed.

- **ChartCap: Mitigating Hallucination of Dense Chart Captioning**
  Junyoung Lim, Jaewoo Ahn, Gunhee Kim — arXiv, 2025
  [Paper (arXiv:2508.03164)](https://arxiv.org/abs/2508.03164)
  565K real-world chart images with dense, hallucination-controlled, cycle-consistency-verified captions.

## Methods / Algorithms

- **DePlot: One-Shot Visual Language Reasoning by Plot-to-Table Translation**
  Fangyu Liu, Julian Martin Eisenschlos, Francesco Piccinno, Syrine Krichene, Chenxi Pang, Kenton Lee, Mandar Joshi, Wenhu Chen, Nigel Collier, Yasemin Altun — Findings of ACL, 2023
  [Paper (arXiv:2212.10505)](https://arxiv.org/abs/2212.10505)
  Bypasses direct visual axis-reading via chart-to-table derendering before LLM reasoning.

- **MatCha: Enhancing Visual Language Pretraining with Math Reasoning and Chart Derendering**
  Fangyu Liu, Francesco Piccinno, Syrine Krichene, Chenxi Pang, Kenton Lee, Mandar Joshi, Yasemin Altun, Nigel Collier, Julian Martin Eisenschlos — ACL, 2023
  [Paper (ACL Anthology)](https://aclanthology.org/2023.acl-long.714/)
  Joint chart-derendering + math-reasoning pretraining; ~20% improvement over prior SOTA on PlotQA/ChartQA.

- **ChartInstruct: Instruction Tuning for Chart Comprehension and Reasoning**
  Ahmed Masry, Mehrad Shahmohammadi, Md Rizwan Parvez, Enamul Hoque, Shafiq Joty — arXiv, 2024
  [Paper (arXiv:2403.09028)](https://arxiv.org/abs/2403.09028)
  191K-instruction, 71K-chart instruction-tuning dataset with end-to-end and pipeline model variants.

- **ChartLlama: A Multimodal LLM for Chart Understanding and Generation**
  Yucheng Han, Chi Zhang, Xin Chen, Xu Yang, Zhibin Wang, Gang Yu, Bin Fu, Hanwang Zhang — arXiv, 2023
  [Paper (arXiv:2311.16483)](https://arxiv.org/abs/2311.16483)
  GPT-4-generated instruction-tuning pipeline for both chart understanding and generation tasks.

- **ChartSketcher: Reasoning with Multimodal Feedback and Reflection for Chart Understanding**
  Muye Huang, Lingling Zhang, Jie Ma, Han Lai, Fangzhi Xu, Yifei Li, Wenjun Wu, Yaqiang Wu, Jun Liu — NeurIPS, 2025
  [Paper (arXiv:2505.19076)](https://arxiv.org/abs/2505.19076)
  Sketch-CoT: model annotates its own reasoning steps directly onto the chart image for iterative visual feedback.

## Applications

- **ChartInsighter: An Approach for Mitigating Hallucination in Time-Series Chart Summary Generation with A Benchmark Dataset**
  Fen Wang, Bomiao Wang, Xueli Shu, Zhen Liu, Zekai Shao, Chao Liu, Siming Chen — IEEE TVCG, 2025
  [Paper (arXiv:2501.09349)](https://arxiv.org/abs/2501.09349)
  Multi-agent, self-consistency-checked pipeline for hallucination-reduced time-series chart summarization.

---

**Note:** An additional reference generated by the source AI paper — attributed to "Kim et al., 2026," titled "Beyond Answer Correctness: Measuring and Reducing Explanation Faithfulness Gaps in Chart Vision Language Models" — was systematically searched for (arXiv, OpenReview, Semantic Scholar, Google Scholar) and **could not be found under any source**. It has been classified as fabricated (Code D) and deliberately excluded from this repository. See the citation-integrity audit for the full search log.