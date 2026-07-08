# Awesome Breast Cancer

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/status-active-blue.svg)

A curated list of datasets, papers, tools, benchmarks, and open-source resources for breast cancer research using Machine Learning, Deep Learning, Medical Imaging, Histopathology, Genomics, Clinical Data Analysis, Explainable AI, and Multimodal Learning.

This repository is designed for researchers, students, engineers, and medical AI developers who want a clean starting point for breast cancer detection, classification, segmentation, prognosis prediction, survival analysis, and trustworthy AI-based diagnosis.

<p align="center">
  <img src="assets/logo.svg" alt="Awesome Breast Cancer Logo" width="180"/>
</p>

---

## Repository Name

Recommended GitHub repository name:

```text
awesome-breast-cancer
```

Readable project title:

```text
Awesome Breast Cancer
```

---

## Latest Updates

- 2026-07-08: Initial GitHub-ready repository created.
- 2026-07-08: Added dataset categories for mammography, ultrasound, histopathology, genomics, clinical, and tabular data.
- 2026-07-08: Added sections for surveys, deep learning, segmentation, explainable AI, multimodal learning, tools, benchmarks, and contribution templates.

---

## Contents

- [Datasets](#datasets)
  - [Mammography Datasets](#mammography-datasets)
  - [Ultrasound Datasets](#ultrasound-datasets)
  - [Histopathology Datasets](#histopathology-datasets)
  - [Genomics and Clinical Datasets](#genomics-and-clinical-datasets)
  - [Tabular Datasets](#tabular-datasets)
- [Research Areas](#research-areas)
- [Papers](#papers)
- [Tools and Libraries](#tools-and-libraries)
- [Code Repositories](#code-repositories)
- [Evaluation Metrics](#evaluation-metrics)
- [Research Directions](#research-directions)
- [Contributing](#contributing)
- [Citation](#citation)
- [License](#license)

---

## Datasets

### Mammography Datasets

| Dataset | Modality | Main Tasks | Link |
|---|---|---|---|
| CBIS-DDSM | Mammography | Classification, detection, segmentation | https://www.cancerimagingarchive.net/collection/cbis-ddsm/ |
| BCDR | Mammography, ultrasound, clinical data | Detection, diagnosis, segmentation | https://bcdr.ceta-ciemat.es/information/about |
| INbreast | Full-field digital mammography | Mass detection, calcification detection, classification | Add access link |
| Mini-MIAS | Mammography | Abnormality detection and classification | Add access link |

### Ultrasound Datasets

| Dataset | Modality | Main Tasks | Link |
|---|---|---|---|
| BUSI | Breast ultrasound | Classification and segmentation | https://www.sciencedirect.com/science/article/pii/S2352340919312181 |
| BUSIS | Breast ultrasound | Tumor segmentation | https://arxiv.org/abs/1801.03182 |
| BUS-UCLM | Breast ultrasound | Lesion segmentation | https://www.nature.com/articles/s41597-025-04562-3 |

### Histopathology Datasets

| Dataset | Modality | Main Tasks | Link |
|---|---|---|---|
| BreakHis | Histopathology | Binary and multiclass classification | https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/ |
| BACH | Histopathology | Classification, whole-slide analysis | https://iciar2018-challenge.grand-challenge.org/Dataset/ |

### Genomics and Clinical Datasets

| Dataset | Modality | Main Tasks | Link |
|---|---|---|---|
| TCGA-BRCA | Genomics, clinical, imaging metadata | Survival analysis, subtype prediction, prognosis | https://portal.gdc.cancer.gov/projects/TCGA-BRCA |
| METABRIC | Genomics and clinical data | Survival analysis, subtype classification | https://www.cbioportal.org/study?id=brca_metabric |

### Tabular Datasets

| Dataset | Modality | Main Tasks | Link |
|---|---|---|---|
| Wisconsin Breast Cancer Diagnostic | Tabular clinical features | Benign vs malignant classification | https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic |
| Wisconsin Breast Cancer Original | Tabular clinical features | Classification | https://archive.ics.uci.edu/dataset/15/breast+cancer+wisconsin+original |
| Breast Cancer Coimbra | Tabular biomedical features | Breast cancer classification | https://archive.ics.uci.edu/dataset/451/breast+cancer+coimbra |

For more details, see [datasets/datasets.md](datasets/datasets.md).

---

## Research Areas

- Breast cancer detection
- Breast cancer classification
- Breast tumor segmentation
- Benign vs malignant prediction
- Mammography-based cancer detection
- Ultrasound-based breast tumor analysis
- Histopathological image classification
- Whole-slide image analysis
- Molecular subtype classification
- Survival analysis and prognosis prediction
- Recurrence prediction
- Treatment response prediction
- Explainable AI for clinical decision support
- Federated learning for privacy-preserving medical AI
- Self-supervised learning for limited labeled medical data
- Multimodal learning using images, genomics, and clinical records
- Bias, fairness, and robustness in breast cancer AI
- Foundation models for pathology and radiology

---

## Papers

### Main Paper Lists

- [Survey Papers](papers/survey-papers.md)
- [Mammography Papers](papers/mammography.md)
- [Ultrasound Papers](papers/ultrasound.md)
- [Histopathology Papers](papers/histopathology.md)
- [Genomics and Clinical Papers](papers/genomics-clinical.md)
- [Explainable AI Papers](papers/explainable-ai.md)
- [Multimodal Breast Cancer Research](papers/multimodal.md)

### Suggested Paper Entry Format

```text
- Paper Title
  - Authors:
  - Venue/Year:
  - Dataset:
  - Task:
  - Method:
  - Code:
  - Notes:
```

---

## Tools and Libraries

See [tools/tools.md](tools/tools.md).

### Common Libraries

- PyTorch: https://pytorch.org/
- TensorFlow: https://www.tensorflow.org/
- Keras: https://keras.io/
- MONAI: https://monai.io/
- SimpleITK: https://simpleitk.org/
- OpenCV: https://opencv.org/
- scikit-image: https://scikit-image.org/
- scikit-learn: https://scikit-learn.org/
- XGBoost: https://xgboost.readthedocs.io/
- LightGBM: https://lightgbm.readthedocs.io/
- SHAP: https://shap.readthedocs.io/
- Captum: https://captum.ai/

---

## Code Repositories

See [code/repositories.md](code/repositories.md).

Suggested code entry format:

```text
- Repository Name
  - Task:
  - Dataset:
  - Framework:
  - Link:
  - Notes:
```

---

## Evaluation Metrics

See [benchmarks/evaluation-metrics.md](benchmarks/evaluation-metrics.md).

### Classification

- Accuracy
- Precision
- Recall
- Sensitivity
- Specificity
- F1-score
- ROC-AUC
- PR-AUC
- Confusion matrix
- Balanced accuracy
- Matthews correlation coefficient

### Segmentation

- Dice coefficient
- Intersection over Union
- Hausdorff distance
- Pixel accuracy
- Boundary F1-score
- Sensitivity
- Specificity

### Survival Analysis

- Concordance index
- Kaplan-Meier analysis
- Hazard ratio
- Log-rank test
- Time-dependent AUC

---

## Research Directions

- Lightweight deep learning models for clinical deployment
- Explainable AI for trustworthy diagnosis
- Federated learning for privacy-preserving breast cancer analysis
- Multimodal learning with imaging, genomics, and clinical data
- Self-supervised learning with limited labeled data
- Domain adaptation across hospitals and imaging devices
- Synthetic data generation and dataset distillation
- Robustness testing across public datasets
- Bias and fairness analysis
- Foundation models for pathology and radiology
- Clinical validation and reproducible benchmarking

---

## Contributing

Contributions are welcome.

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

You can contribute by adding:

- New datasets
- Recent papers
- Open-source code
- Benchmark results
- Survey papers
- Useful tools
- Reproducible experiments

---

## Citation

If you find this repository useful, please consider starring it and citing it.

```bibtex
@misc{awesome_breast_cancer,
  title        = {Awesome Breast Cancer},
  author       = {Your Name},
  year         = {2026},
  howpublished = {\url{https://github.com/atikuzzaman524/Awesome-Breast-Cancer}},
  note         = {A curated list of breast cancer datasets, papers, tools, and resources}
}
```

---

## Disclaimer

This repository is for research and educational purposes only. It does not provide medical advice, diagnosis, or treatment. Always follow dataset licenses, ethical approval requirements, data use agreements, and privacy regulations.

---

## License

This project is released under the MIT License. See [LICENSE](LICENSE).
