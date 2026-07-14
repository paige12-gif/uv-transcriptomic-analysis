# UV Transcriptomic Analysis

Python-based RNA-seq analysis of UV-induced transcriptomic changes in human dermal fibroblasts.

---

# Project Overview

Ultraviolet (UV) radiation is a major environmental factor contributing to skin aging by inducing widespread molecular changes in dermal fibroblasts. While many transcriptomic studies focus on identifying individual differentially expressed genes (DEGs), biological responses arise from coordinated regulation of multiple pathways rather than isolated genes.

This project applies differential gene expression analysis and Gene Ontology (GO) enrichment to investigate biological processes altered by UV exposure from a systems biology perspective.

**Key Skills**

- Python
- RNA-seq analysis
- Differential Gene Expression (DEG)
- Gene Ontology (GO) enrichment
- Data visualization
- Systems Biology
---

# Research Question

**Which coordinated biological processes are altered in UV-exposed human dermal fibroblasts, and do these transcriptomic changes reflect chronic photoaging or an acute UV stress response?**

---

# Dataset

- **Source:** NCBI Gene Expression Omnibus (GEO)
- **Accession:** GSE119009
- **Cell type:** Normal Human Dermal Fibroblasts (NHDF)
- **Comparison:** UV-treated vs Control

---

# Workflow

RNA-seq data

↓

Differential Gene Expression (DEG) Analysis

↓

Volcano Plot

↓

GO Biological Process Enrichment

↓

Representative Gene Selection

↓

Heatmap & Biological Process Comparison

---

# Methods

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- GSEAPY (GO enrichment)

Analysis included:

- Differential expression analysis
- Volcano plot visualization
- GO Biological Process enrichment
- Representative gene heatmap
- Biological process comparison (boxplot)

---

# Results

## Differential Gene Expression

![Volcano Plot](Volcano_plot_final.png)

Differential expression analysis identified genes significantly altered following UV exposure. Genes with |log2FC| ≥ 1 and p < 0.05 were classified as differentially expressed.

## GO Biological Process Enrichment

### Upregulated Biological Processes

![GO Up](GO_upregulated_barplot.png)

GO enrichment analysis identified significant enrichment of metabolic processes, particularly branched-chain amino acid metabolism, among upregulated genes.

### Downregulated Biological Processes

![GO Down](GO_downregulated_barplot.png)

Downregulated genes were enriched in biological processes related to cell proliferation, angiogenesis, and regulation of apoptosis, suggesting coordinated suppression of multiple biological programs following UV exposure.

## Representative Gene Expression

![Heatmap](Heatmap_GO_expression.png)

Representative genes from enriched biological processes were visualized to illustrate coordinated expression changes across biological pathways rather than isolated gene-level alterations.

---

## GO Biological Process Enrichment

GO enrichment revealed coordinated transcriptomic changes rather than isolated gene-level alterations.

Major enriched biological processes included:

- Branched-chain amino acid metabolism
- Cell population proliferation
- Angiogenesis
- Regulation of apoptotic processes

---

## Systems-Level Interpretation

Rather than examining individual genes alone, this project interpreted transcriptomic responses at the biological process level.

The enrichment results suggest that acute UV exposure induces coordinated changes in metabolism, proliferation, angiogenesis, and apoptosis, indicating system-level transcriptional reprogramming.

---

# Limitations

- Single RNA-seq dataset
- Single post-irradiation time point
- GO enrichment identifies statistically enriched biological processes but does not establish causal regulatory relationships.

---

# Future Work

Potential future extensions include:

- Time-course RNA-seq analysis
- Single-cell RNA-seq
- Gene regulatory network analysis
- Pathway network modeling

---

# Skills Demonstrated

- RNA-seq data analysis
- Differential gene expression analysis
- Gene Ontology enrichment
- Python data analysis
- Data visualization
- Biological interpretation
- Systems biology thinking
