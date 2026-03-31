
### Performance Consistency across Benchmarks

[📊 View High-Resolution Analysis (PDF)](./image/consistency.pdf)

This figure demonstrates the performance alignment of five leading T2I models across established benchmarks (GenEval, DPG) and our VIOLIN benchmark (Variation 1 Color Precision, Variation 1 Color Purity).

To facilitate direct comparison across varying scales, all metrics are normalized to [0,1], with Color Precision and Color Purity inverted such that higher scores represent superior performance for all dimensions.

The high degree of trend covariance across all four dimensions suggests that VIOLIN effectively captures the core generative capabilities of these models.


### Edited Figure 3

[📊 View Edited Figure 3 (PDF)](./image/edited_fig3.pdf)


### Sensitivity Analysis

[📊 View Sensitivity Analysis Results (PDF)](./image/sensitivity.pdf)

We evaluate **Color Purity** (left) and **Color Precision** (right) by biasing weights. The **Uniform** bars represent the equal-weight baseline $w_i = 1/N$, while other bars represent schemes where a single weight $w_i$ is increased (e.g., to 0.8) and the remainder is split uniformly. The largely stable model rankings demonstrate that VIOLIN is robust and insensitive to specific weight tuning.


### Fine-tuning Results

[📊 View Fine-tuning Results (PDF)](./image/finetune.pdf)
