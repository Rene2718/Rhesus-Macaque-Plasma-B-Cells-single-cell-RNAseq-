# Rhesus Macaque Plasma B Cells ‒ Single‑Cell RNA‑seq

## Overview

This repository contains analysis code and notebooks for single‑cell RNA sequencing of plasma B cells from rhesus macaque. The aim is to explore differential expression, cell state heterogeneity, and investigate transcriptome/RNA velocity relevant to plasma B cell biology.

## Contents

| File / Folder | Description |
|---------------|-------------|
| `data cleanup_pre-analysis.ipynb` | Initial data cleaning & QC steps; filtering, normalization, metadata handling. |
| `scanpy_NHP_exlight.ipynb`       | Exploratory data analysis with Scanpy: UMAP, clustering, marker gene analysis. |
| `DEG analysis.ipynb`              | Differential expression (DEG) between specified groups (e.g., cell clusters, isotypes). |
| `.DS_Store`                       | macOS metadata file – not needed; should be ignored. |

