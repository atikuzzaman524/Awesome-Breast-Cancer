# Breast Cancer Datasets

This file contains a structured list of useful public and semi-public breast cancer datasets for machine learning, deep learning, medical imaging, histopathology, genomics, and clinical data analysis.

---

## Mammography Datasets

### CBIS-DDSM

- **Full Name:** Curated Breast Imaging Subset of Digital Database for Screening Mammography
- **Modality:** Mammography
- **Tasks:** Classification, detection, segmentation
- **Labels:** Normal, benign, malignant
- **Use Cases:** Computer-aided diagnosis, mass classification, calcification detection, lesion segmentation
- **Link:** https://www.cancerimagingarchive.net/collection/cbis-ddsm/
- **Notes:** Widely used for mammography-based breast cancer AI research.

### BCDR

- **Full Name:** Breast Cancer Digital Repository
- **Modality:** Mammography, ultrasound, clinical records, lesion annotations
- **Tasks:** Detection, diagnosis, segmentation, image descriptor analysis
- **Link:** https://bcdr.ceta-ciemat.es/information/about
- **Notes:** Contains mammography and ultrasound cases with clinical history and lesion segmentation.

### INbreast

- **Modality:** Full-field digital mammography
- **Tasks:** Mass detection, calcification detection, classification, segmentation
- **Labels:** Normal, benign, malignant, BI-RADS-related annotations
- **Link:** Add access link
- **Notes:** Often requires access request or data-use agreement.

### Mini-MIAS

- **Full Name:** Mini Mammographic Image Analysis Society Database
- **Modality:** Mammography
- **Tasks:** Abnormality detection, classification
- **Link:** Add access link
- **Notes:** Frequently used in classical image processing and ML-based mammography studies.

---

## Ultrasound Datasets

### BUSI

- **Full Name:** Breast Ultrasound Images Dataset
- **Modality:** Breast ultrasound
- **Tasks:** Classification, segmentation
- **Classes:** Normal, benign, malignant
- **Link:** https://www.sciencedirect.com/science/article/pii/S2352340919312181
- **Notes:** Frequently used for ultrasound tumor classification and segmentation.

### BUSIS

- **Full Name:** Breast Ultrasound Image Segmentation Benchmark
- **Modality:** Breast ultrasound
- **Tasks:** Tumor segmentation
- **Link:** https://arxiv.org/abs/1801.03182
- **Notes:** Useful for segmentation benchmarking.

### BUS-UCLM

- **Full Name:** Breast Ultrasound Lesion Segmentation Dataset
- **Modality:** Breast ultrasound
- **Tasks:** Lesion segmentation
- **Link:** https://www.nature.com/articles/s41597-025-04562-3
- **Notes:** Useful for modern segmentation research.

---

## Histopathology Datasets

### BreakHis

- **Full Name:** Breast Cancer Histopathological Image Classification Dataset
- **Modality:** Histopathology
- **Tasks:** Binary classification, multiclass classification
- **Classes:** Benign and malignant breast tumors
- **Magnification Levels:** 40X, 100X, 200X, 400X
- **Link:** https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/
- **Notes:** Common dataset for histopathology image classification.

### BACH

- **Full Name:** Breast Cancer Histology Images Dataset
- **Modality:** H&E-stained histopathology images and whole-slide images
- **Tasks:** Classification and whole-slide analysis
- **Classes:** Normal, benign, in situ carcinoma, invasive carcinoma
- **Link:** https://iciar2018-challenge.grand-challenge.org/Dataset/
- **Notes:** Released through the ICIAR 2018 Grand Challenge.

---

## Genomics and Clinical Datasets

### TCGA-BRCA

- **Full Name:** The Cancer Genome Atlas Breast Invasive Carcinoma
- **Modality:** Genomics, transcriptomics, clinical data
- **Tasks:** Molecular subtype classification, survival analysis, prognosis prediction
- **Link:** https://portal.gdc.cancer.gov/projects/TCGA-BRCA
- **Notes:** One of the most important public cancer genomics resources.

### METABRIC

- **Full Name:** Molecular Taxonomy of Breast Cancer International Consortium
- **Modality:** Genomics and clinical data
- **Tasks:** Survival analysis, subtype classification, prognosis prediction
- **Link:** https://www.cbioportal.org/study?id=brca_metabric
- **Notes:** Commonly used for breast cancer molecular subtype and survival analysis.

---

## Tabular Datasets

### Wisconsin Breast Cancer Diagnostic

- **Modality:** Tabular clinical features
- **Tasks:** Benign vs malignant classification
- **Link:** https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
- **Notes:** A popular introductory dataset for classical ML classification.

### Wisconsin Breast Cancer Original

- **Modality:** Tabular clinical features
- **Tasks:** Classification
- **Link:** https://archive.ics.uci.edu/dataset/15/breast+cancer+wisconsin+original
- **Notes:** Earlier Wisconsin breast cancer dataset.

### Breast Cancer Coimbra

- **Modality:** Tabular biomedical features
- **Tasks:** Breast cancer classification
- **Link:** https://archive.ics.uci.edu/dataset/451/breast+cancer+coimbra
- **Notes:** Includes quantitative predictors and a binary target variable.

---

## Dataset Contribution Template

```text
### Dataset Name

- Full Name:
- Modality:
- Tasks:
- Classes/Labels:
- Number of Samples:
- Format:
- Link:
- License:
- Notes:
```
