# README
Here's a draft README file for the GitHub repository you provided:

# Acute Myeloid Leukemia Heatmap Analysis

This repository contains R code for creating a heatmap visualization of gene expression data from acute myeloid leukemia (AML) samples. The analysis is adapted from the refine.bio-examples notebook and focuses on clustering and visualizing RNA-seq data from AML model mice.

## Purpose

The goal of this analysis is to:

1. Load and preprocess RNA-seq data from AML model mice samples
2. Perform clustering on gene expression data
3. Create an annotated heatmap visualization of the clustered data
4. Identify genes with high variance across samples

## Data Source

This analysis uses publicly available RNA-seq data from AML model mice samples obtained from Shih et al., 2017 [2]. The data was pre-processed and quantile normalized by refine.bio [3].

## Setup

Before running the analysis, ensure you have the following installed:

- R
- RStudio
- Required R packages (listed in the script)

Create a new directory for this project and clone the repository:

```bash
mkdir aml_heatmap_analysis
cd aml_heatmap_analysis
git clone https://github.com/yourusername/aml_heatmap_analysis.git
```

## Running the Analysis

1. Open the main R script (e.g., `aml_heatmap_analysis.Rmd`)
2. Install required packages if not already installed
3. Run the entire script in RStudio or copy/paste into an R console

## Output

The analysis produces several outputs:

- A PNG image of the annotated heatmap (`aml_heatmap.png`)
- A TSV file of top 90% variance genes (`top_90_var_genes.tsv`)
- Session info for reproducibility

## References

[2] Shih, A. H., Wang, Y., Lin, M., McGraw, K., James, D. J., Hatlen, M. G., ... & Armstrong, S. A. (2017). Exploiting synthetic lethality between GLI1 and CDK9 in acute myeloid leukemia. Nature Medicine, 23(11), 1388-1395.

[3] refine.bio documentation: http://docs.refine.bio/en/latest/main_text.html#refine-bio-processed-refinebio-processedibadge

## Contact

For questions or feedback, please open an issue on this GitHub repository.

---

This README provides an overview of the project, its purpose, setup instructions, and expected outputs. It also includes references to the original data source and any relevant documentation. You can customize this further based on your specific needs and preferences.

Citations:
[1] https://github.com/philipjsweet/R_heatmaps
[2] https://github.com/BCCHR-trainee-omics-group/StudyGroup/blob/master/workshops/RNA-seq-Workshop-2021/Pre_Workshop_ToDos.md
[3] https://github.com/AG-JY-Lab/RNA-seq-analysis/
[4] https://git.embl.de/provazni/rna-seq-tutorial
[5] https://github.com/jokergoo/InteractiveComplexHeatmap/blob/master/README.md
[6] https://github.com/RibosomeCRCL/ribomethseq-nf/blob/main/README.md
[7] https://github.com/nanxstats/dockflow/blob/master/workflow/rnaseq-gene/src/vignettes/index.Rmd
[8] https://github.com/baj12/scShinyHub/blob/master/README.md
[9] https://ciri.gitbiopages.ens-lyon.fr/bibs/carine/rnaseq_analysis_training/Session_5.html
[10] https://angus.readthedocs.io/en/2019/rmarkdown_rnaseq.html
