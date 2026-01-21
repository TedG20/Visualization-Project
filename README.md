# Bioinformatics Data Visualization Project

**Visualizing Gene Expression Data**  
Transforming raw expression matrices into clear, interpretable visual stories.

---

## Overview
Visualization is the secret ingredient that makes a portfolio shine—it’s where science meets design. This project demonstrates how to take a public gene expression dataset and produce **clean, insightful plots** that highlight meaningful biological patterns.

The dataset used here is from **GEO (GSE161369)**, but any public expression dataset can be used. The focus is on **clarity and reproducibility**, not complexity.

---

## Key Visualizations
1. **Heatmap of Top Variable Genes**  
   - Shows patterns of gene expression across samples.  
   - Helps identify clusters of similar expression profiles.

2. **Volcano Plot**  
   - Highlights significantly differentially expressed genes.  
   - Makes it easy to spot genes with both high effect and statistical significance.

> These visualizations are instantly recognizable in the bioinformatics community and demonstrate practical data visualization skills.

---

## Project Structure
```text
viz-project/
├── data/
│   └── GSE161369_series_matrix.txt.gz
├── figures/
│   ├── heatmap.png
│   └── volcano.png
├── notebook.ipynb
└── README.md
