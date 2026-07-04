# Integrated Transcriptomic Analysis of Alzheimer's Disease

## Overview

This repository contains the complete bioinformatics workflow, processed results, figures, and dissertation accompanying an integrated transcriptomic analysis of Alzheimer's disease (AD).

The study integrates two independent Gene Expression Omnibus (GEO) microarray datasets to identify reproducible differentially expressed genes (DEGs), investigate enriched biological pathways, and identify key hub genes through protein–protein interaction network analysis.

---

## Study Objectives

The objectives of this project were to:

- Identify differentially expressed genes in Alzheimer's disease.
- Integrate independent transcriptomic datasets to identify robust shared DEGs.
- Perform Gene Ontology (GO) enrichment analysis.
- Perform KEGG pathway enrichment analysis.
- Construct protein–protein interaction (PPI) networks.
- Identify highly connected hub genes potentially involved in Alzheimer's disease pathology.

---

## Datasets

The analyses were performed using publicly available datasets from the NCBI Gene Expression Omnibus (GEO):

- **GSE122063**
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE122063

- **GSE33000**
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE33000

Raw GEO files are **not included** in this repository because they are publicly available through the GEO database and exceed GitHub's file size limits.

---

## Repository Structure

```text
alzheimers-transcriptomic-analysis/
│
├── notebooks/
│   ├── Notebook_A.ipynb
│   ├── Notebook_B.ipynb
│   └── Notebook_C.ipynb
│
├── figures/
│   ├── Dataset1/
│   ├── Dataset2/
│   └── Integrated/
│
├── results/
│   ├── Dataset1/
│   ├── Dataset2/
│   └── Integrated/
│
├── Paper.pdf
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Analysis Workflow

The project consists of three Jupyter notebooks.

### Notebook A

- Data preprocessing
- Sample annotation
- Quality assessment
- Differential expression analysis of GSE122063

### Notebook B

- Data preprocessing
- Differential expression analysis of GSE33000

### Notebook C

- Integrated analysis
- Identification of shared DEGs
- GO enrichment analysis
- KEGG pathway enrichment analysis
- STRING protein interaction network analysis
- Hub gene identification
- Figure generation

---

## Software Requirements

The analyses were performed using Python.

Main packages include:

- numpy
- pandas
- scipy
- matplotlib
- seaborn
- scikit-learn
- statsmodels
- networkx
- gseapy

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## Main Findings

- 914 significant DEGs identified in **GSE122063**
- 320 significant DEGs identified in **GSE33000**
- 113 shared differentially expressed genes identified through integrated analysis
- Significant enrichment of synaptic signalling, calcium signalling and immune-related biological processes
- Identification of multiple highly connected hub genes including:

- SST
- PVALB
- GAD1
- GAD2
- SNAP25
- CRH
- BDNF

---

## Results

The repository contains:

- Differential expression tables
- Volcano plots
- PCA plots
- Heatmaps
- GO enrichment figures
- KEGG enrichment figures
- Protein–protein interaction networks
- Hub gene network visualisations

---

## Dissertation

The complete research dissertation is available as:

```
Analysis.pdf
and
Analysis.docx
```

---

## Citation

If you use this repository or its results, please cite:

> Rita Ellinidou. (2026). **Integrated Transcriptomic Analysis of Alzheimer's Disease**. Independent Bioinformatics Research Project.

---

## License

This repository is provided for educational and research purposes.

The original datasets remain the property of the National Center for Biotechnology Information (NCBI) Gene Expression Omnibus.

---

## Acknowledgements

This project utilised publicly available transcriptomic datasets from the NCBI Gene Expression Omnibus (GEO). The authors gratefully acknowledge the original investigators who generated and shared these datasets, enabling reproducible bioinformatics research.
