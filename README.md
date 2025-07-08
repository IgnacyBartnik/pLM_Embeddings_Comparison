# pLM_Embeddings_Comparison

This repository demonstrates the use of state-of-the-art protein language models (pLMs) for analyzing protein sequence embeddings. It showcases a workflow for selecting proteins from the UniRef50 dataset, generating embeddings using ESM2 and ProtT5 models, and visualizing the resulting representations with dimensionality reduction techniques such as UMAP, t-SNE, and PCA.

## Overview

- **Protein Selection:** A subset of protein sequences is chosen from the UniRef50 database.
- **Embedding Generation:** Embeddings are computed using two leading transformer-based models: ESM2 (by Meta AI) and ProtT5 (by Rostlab).
- **Analysis & Visualization:** The high-dimensional embeddings are projected into two dimensions using UMAP, t-SNE, and PCA to explore clustering and structural patterns in the data.

## Features

- End-to-end pipeline for protein embedding generation and analysis.
- Comparison of different pLM architectures and their representations.
- Interactive and publication-ready visualizations.
- Example notebook for reproducibility and easy experimentation.

## Requirements

- Python 3.8+
- Jupyter Notebook
- PyTorch
- Hugging Face Transformers
- UMAP-learn
- scikit-learn
- pandas, numpy, matplotlib, plotly

Install dependencies with:
```bash
pip install -r requirements.txt
```

## Usage

1. **Download or clone this repository.**
2. **Prepare a subset of UniRef50 protein sequences (see notebook for details).**
3. **Run the Jupyter notebook `embeddings_demo.ipynb` to generate embeddings and visualizations.**
4. **Export results as HTML or images for sharing or inclusion in your portfolio.**

## About

This project was developed as a demonstration of modern machine learning techniques in computational biology, with a focus on protein representation learning. It is intended to showcase practical skills in deep learning, bioinformatics, and scientific visualization.

For questions or collaboration, please reach out to me at IgnacyABartnik@gmail.com
