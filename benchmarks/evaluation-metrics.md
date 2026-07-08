# Evaluation Metrics and Benchmarking

This file summarizes common evaluation metrics for breast cancer AI research.

---

## Classification Metrics

### Accuracy

```text
Accuracy = Correct Predictions / Total Predictions
```

Useful when the dataset is balanced. It may be misleading when classes are imbalanced.

### Precision

```text
Precision = TP / (TP + FP)
```

Useful when false positives are costly.

### Recall or Sensitivity

```text
Recall = TP / (TP + FN)
```

Important in medical diagnosis because missing cancer cases can be serious.

### Specificity

```text
Specificity = TN / (TN + FP)
```

Measures how well the model identifies non-cancer or benign cases.

### F1-score

```text
F1 = 2 * (Precision * Recall) / (Precision + Recall)
```

Useful when the dataset is imbalanced.

### ROC-AUC

Measures the ability of a classifier to separate classes across decision thresholds.

### PR-AUC

Useful for highly imbalanced datasets.

### Confusion Matrix

A table showing true positives, true negatives, false positives, and false negatives.

---

## Segmentation Metrics

### Dice Coefficient

```text
Dice = 2|A ∩ B| / (|A| + |B|)
```

Measures overlap between predicted mask and ground truth mask.

### Intersection over Union

```text
IoU = |A ∩ B| / |A ∪ B|
```

Also called Jaccard index.

### Hausdorff Distance

Measures boundary mismatch between predicted and ground truth masks.

### Pixel Accuracy

Measures the percentage of correctly classified pixels.

---

## Survival Analysis Metrics

### Concordance Index

Measures how well predicted risk scores agree with actual survival ordering.

### Kaplan-Meier Analysis

Used to compare survival curves between different groups.

### Log-rank Test

Used to test whether survival curves are significantly different.

### Hazard Ratio

Measures relative risk between groups.

---

## Reporting Checklist

When reporting results, include:

- Dataset name
- Number of samples
- Train, validation, and test split
- Class distribution
- Preprocessing steps
- Model architecture
- Hyperparameters
- Evaluation metrics
- Confidence intervals when possible
- External validation when possible
- Code and random seed when possible
