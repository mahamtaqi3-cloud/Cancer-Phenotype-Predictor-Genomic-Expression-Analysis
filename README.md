# Cancer Phenotype Predictor: Genomic Expression Analysis

## Project Overview

This project explores the use of machine learning to predict cancer presence based on genomic gene expression profiles. By leveraging tree-based classification models, this project demonstrates how non-linear relationships in gene data can be modeled to provide high-accuracy diagnostic predictions.

## Objective

To develop and evaluate a binary classification model capable of distinguishing between malignant and benign phenotypes using gene expression as primary features.

## Methodology

1. **Data Acquisition:** Loaded processed gene expression datasets.
2. **Exploratory Data Analysis (EDA):** Visualized feature distributions and identified non-linear, interlinked class boundaries.
3. **Model Selection:** Compared linear models (Logistic Regression) against non-linear models (Random Forest).
4. **Training & Evaluation:** Employed a Random Forest Classifier to achieve a final accuracy of 91%.
5. **Interpretability:** Used feature importance analysis to quantify the predictive contribution of specific genomic markers.

## Key Findings

* **Non-Linearity:** Genomic interactions in this dataset exhibit complex non-linear patterns that require ensemble learning methods for optimal classification.
* **Predictive Power:** Random Forest models successfully captured the underlying feature space, significantly outperforming linear baseline models.
* **Feature Contribution:** "Gene One" and "Gene Two" were identified as having balanced importance in determining the clinical phenotype.

## Technical Stack

* **Language:** Python
* **Libraries:** `pandas`, `scikit-learn`, `matplotlib`, `seaborn`
* **Environment:** Google Colab

## Next Steps

* **High-Dimensional Scaling:** Transitioning from two-feature models to large-scale TCGA Pan-Cancer datasets.
* **Ortholog Mapping:** Connecting these computational findings to identified orthologous genes in *Drosophila* models.
* **Clinical Metrics:** Implementing deeper evaluation via confusion matrices to minimize false negatives in a medical diagnostic context.

---

