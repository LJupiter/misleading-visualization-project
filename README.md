# Detecting Misleading Visualizations with LLMs

This project evaluates how well AI models can detect misleading data visualizations, using a set of 100 real-world charts and a taxonomy of common visual deception techniques.

## 📊 Project Overview

- **Goal:** Test the ability of a large language model (LLM) to classify misleading visualizations across multiple prompt strategies.
- **Methodology:** A set of zero-shot, two-shot, and four-shot prompts were used to evaluate the same 100 visualizations. Each prompt asked the model to:
  1. Classify whether the visualization is misleading,
  2. Explain its reasoning,
  3. Identify the misleading element.
- **Taxonomy Reference:** Categories are derived from *Misinformed by Visualization* (Lo et al., 2022).

## 📌 Key Variables

The dataset used in the notebook includes:
- `Prompt`: The prompting condition (zero-shot, two-shot, four-shot)
- `Cluster`: Visualization type group
- `Classification`: Whether the model judged the image as misleading
- `Explanation`: Model's rationale
- `Alignment`: How well the explanation aligned with the taxonomy
- `Precision`: Scoring of explanation quality

## 📜 License
This project is licensed under the [MIT License](LICENSE).
