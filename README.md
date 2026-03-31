
### Performance Consistency across Benchmarks

[📊 View High-Resolution Analysis (PDF)](./image/consistency.pdf)

This figure demonstrates the performance alignment of five leading T2I models across established benchmarks (**GenEval**, **DPG**) and our **VIOLIN** benchmark (**Color Precision**, **Color Purity**). 
The consistent ranking across all four dimensions suggests that VIOLIN effectively captures the core generative capabilities of these models and highlights a universal limitation in precise color obedience.


### Model Ranking Comparison (Fig. 3)

[📊 View Edited Figure 3 (PDF)](./image/edited_fig3.pdf)


### Sensitivity Analysis

[📊 View Sensitivity Analysis Results (PDF)](./image/sensitivity.pdf)

We evaluate **Color Purity** (left) and **Color Precision** (right) by biasing weights. The **Uniform** bars represent the equal-weight baseline $w_i = 1/N$, while other bars represent schemes where a single weight $w_i$ is increased (e.g., to $0.8$) and the remainder is split uniformly. The largely stable model rankings demonstrate that VIOLIN is robust and insensitive to specific weight tuning.


### Fine-tuning Results

[📊 View Fine-tuning Results (PDF)](./image/finetune.pdf)
