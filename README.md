  # CMV-RNAseq-Bioinformatics-Analysis
Integrated RNA-seq bioinformatics workflow extending wet-lab HCMV studies through differential expression, functional enrichment, STRING PPI, Cytoscape, hub gene prioritization, and MCODE analysis to uncover key molecular mechanisms, functional modules, and candidate biomarkers for placental and congenital HCMV infection.

🧬 Comprehensive Bioinformatics Analysis of Human Cytomegalovirus (HCMV) Infection

📖 Overview

This repository presents an integrated RNA-seq bioinformatics workflow investigating host molecular responses to Human Cytomegalovirus (HCMV) infection in human trophoblast stem cells (hTSCs). The study combines transcriptomics and systems biology approaches to identify differentially expressed genes, enriched pathways, protein interaction networks, hub genes, and functional gene modules associated with placental HCMV infection.



 ## 🧪 Dataset

| **Feature** | **Description** |
|-------------|-----------------|
| **Organism** | *Homo sapiens* |
| **Tissue** | Placenta |
| **Sample Type** | Human trophoblast stem cells (hTSCs) |
| **Cell Lines** | CT27, CT29 |
| **Infection** | Human Cytomegalovirus (HCMV) |
| **Platform** | Illumina NovaSeq (RNA-seq, paired-end sequencing)

## 🔬 Bioinformatics Workflow

|**Step**| **Workflow**|
|--------|-------------|
1|RNA-seq Dataset Acquisition (GEO)| Raw gene expression dataset|
2|Quality Assessment| High-quality expression data|
3| Differential Expression Analysis (GEO2R/DESeq2)| Differentially Expressed Genes (DEGs)|
4| Principal Component Analysis (PCA)| Sample clustering plot|
5| Volcano Plot Analysis| Significant upregulated & downregulated genes|
6| Heatmap Analysis| Expression pattern of top DEGs|
7|Functional Enrichment Analysis (GO, Reactome, WikiPathways)| Enriched biological pathways|
8| STRING Protein–Protein Interaction (PPI) Network| Protein interaction network|
9| Cytoscape Network Visualization| Network visualization|
10| Hub Gene Identification| Highly connected hub genes|
11| MCODE Cluster Analysis| Functional gene modules (Cluster 1)
12| Biological Interpretation| Candidate biomarkers & molecular mechanisms

## 🛠 Tools & Software

|**Software**| **Purpose**|
|------------|------------|
|GEO| RNA-seq Dataset|
|GEO2R / DESeq2| Differential Expression Analysis|
|EnhancedVolcano| Volcano Plot|
|pheatmap| Heatmap|
|STRING| Protein–Protein Interaction Network|
|Cytoscape| Network Visualization|
|MCODE| Cluster Detection|
|Enrichr| Functional Enrichment|

📊 Results

✅ Differentially Expressed Genes (DEGs)

✅ PCA Plot

✅ Volcano Plot

✅ Heatmap

✅ GO Enrichment

✅ Reactome Analysis

✅ WikiPathways Analysis

✅ STRING PPI Network

✅ Hub Gene Identification

✅ MCODE Cluster Detection

🖼 Figure

### 🌋 Volcano Plot

**Description:** Displays significantly upregulated and downregulated genes based on log2 fold change and adjusted p-value, highlighting genes most affected by HCMV infection.

<img width="636" height="528" alt="image" src="https://github.com/user-attachments/assets/7d056628-90d2-4d32-9817-2179ae4897d8" />

### 📈 PCA Plot
**Description:** Principal Component Analysis (PCA) showing the overall variation in gene expression and clear separation between HCMV-infected and control samples.

<img width="800" height="600" alt="CMV_PCA_plot" src="https://github.com/user-attachments/assets/66065f22-758a-4e75-8161-d4af3144ee1c" />

### 🔥 Heatmap
**Description:* Displays the expression patterns of the top differentially expressed genes across all samples, illustrating distinct clustering between infected and control groups.

<img width="636" height="528" alt="CMV_top50_heatmap" src="https://github.com/user-attachments/assets/0c98aa92-8b01-4fe8-94f2-d1f7a42534db" />

### 🔗 STRING Protein–Protein Interaction Network
**Description:** Protein–protein interaction (PPI) network illustrating functional interactions among differentially expressed genes and identifying key molecular relationships.

<img width="1800" height="1984" alt="CMV_STRING_PPI_network_highres" src="https://github.com/user-attachments/assets/3618457d-2393-4a78-ad81-1ed78040115c" />

### 🧩 MCODE Cluster 1
**Description:**  Highest-scoring functional module identified using the MCODE algorithm, representing a densely interconnected protein cluster with potential biological significance in HCMV infection.

<img width="1047" height="350" alt="CMV_MCODE_Cluster1" src="https://github.com/user-attachments/assets/e682c023-c9c9-4e3c-9318-1540b942817b" />

### 📊 GO Biological Process Enrichment
**Description:** Bar plot showing significantly enriched biological processes associated with the differentially expressed genes, providing functional insight into HCMV infection.

<img width="1058" height="450" alt="CMV_Cluster1_Enrichment_barplot png" src="https://github.com/user-attachments/assets/820982c3-5a54-4022-931a-f2c00f05fc49" />

### 🚀 Future Work

Drug target prediction.
Machine learning-based biomarker discovery.
Clinical validation in maternal–fetal infection cohorts.

### ✅ Citation

If you use this repository in your research, please cite the associated publication or acknowledge this GitHub repository.

#### 👨‍💻Author

  FANNY R 

### 📄Licence

  MIT Licence
