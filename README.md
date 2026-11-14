# TADP — Provenance-Driven Client Governance for Federated Learning

This repository contains the experimental code supporting the manuscript **“Provenance-Driven Client Governance for Federated Learning.”**

### Experiments
- **Datasets:** Adult (Census Income) and Fashion-MNIST.
- **Setup:** 50 simulated clients per dataset, five random seeds (42–46), and two non-IID settings (α = 0.5 and 0.1).
- **Conditions:** Clean and degraded training data.
- **Methods:** HPG, PWA, WUPW, comparison methods, and ablation studies.

### Reproducibility
The numbered notebooks contain the experiments reported in the manuscript. Each notebook can be executed in Google Colab using its specified configuration.

The experiments use eight automated data-quality factors and 20 synthetically generated documentary factors.

### Datasets
- [Adult — UCI Repository](https://archive.ics.uci.edu/dataset/2/adult)
- [Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist)

### Note
The study uses simulated clients and synthetic documentary assessments. It does not validate real-world documentary evidence or regulatory compliance.
