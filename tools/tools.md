# Tools and Libraries

## DePlot
**Purpose:** Modality-conversion module that derenders a chart image into a linearized data table, letting a standard LLM reason over structured text instead of pixels — sidestepping direct visual axis-reading errors entirely.
**Link:** [Paper & Code Pointers (arXiv:2212.10505)](https://arxiv.org/abs/2212.10505)

## MatCha
**Purpose:** A Pix2Struct-based pretraining recipe combining chart-derendering and math-reasoning objectives, improving both layout/axis understanding and downstream numerical reasoning.
**Link:** [Google Research Publication Page](https://research.google/pubs/matcha-enhancing-visual-language-pretraining-with-math-reasoning-and-chart-derendering/)

## UniChart
**Purpose:** A universal pretrained chart-comprehension model combining low-level tasks (extracting bars, lines, and axis-grounded data) with high-level reasoning objectives.
**Link:** [Paper (ACL Anthology)](https://aclanthology.org/2023.emnlp-main.906/)

## ChartInstruct
**Purpose:** Instruction-tuning dataset (191K instructions, 71K charts) and two model architectures (end-to-end and chart-to-table pipeline) for general chart comprehension and reasoning.
**Link:** [Model Cards (Hugging Face)](https://huggingface.co/ahmed-masry/ChartInstruct-FlanT5-XL)

## ChartSketcher
**Purpose:** Multimodal feedback-driven reasoning model (built on Qwen2VL-72B) that lets the model sketch its own intermediate reasoning directly onto the chart image — e.g., drawing a line from a data point to the axis to read its value — then iterates on that visual feedback.
**Link:** [GitHub — MuyeHuang/ChartSketcher](https://github.com/MuyeHuang/ChartSketcher)