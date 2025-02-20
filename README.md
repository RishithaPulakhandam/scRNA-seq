## **Single-Cell RNA Sequencing Analysis**  

This repository contains an R-based pipeline for analyzing **single-cell RNA sequencing (scRNA-seq) data**. The analysis includes preprocessing, clustering, visualization, and annotation of cell types.  

### **Overview**  
This project performs:  
- **Data Preprocessing:** Filtering, normalization, and quality control of scRNA-seq data.  
- **Dimensionality Reduction:** PCA and UMAP for clustering and visualization.  
- **Cell Type Annotation:** Identification of major immune cell types using marker genes.  
- **Differential Expression Analysis:** Identifying significant gene expression differences across clusters.  

### **Files in this Repository**  
- `ScRNA-Seq.Rmd` → R Markdown file with the full analysis pipeline.  
- `ScRNA-Seq.pdf` → Rendered PDF output of the analysis.   
- `README.md` → Project documentation (this file).  

### **Installation & Dependencies**  
To run this analysis, install the following R packages:  
```r
install.packages(c("Seurat", "dplyr", "SeuratObject, "patchwork"))
```
### **How to Run the Analysis**  
1. Open `ScRNA-Seq.Rmd` in RStudio.  
2. Run the code chunks sequentially or knit the document to generate an HTML report.  

### **Results**  
- The UMAP visualization shows distinct clusters representing different immune cell populations.  
- Differential expression analysis identifies key marker genes distinguishing cell types.  
