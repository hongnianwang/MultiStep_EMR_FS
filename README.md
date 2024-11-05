# Constructing an effective and practical multi-step feature selection framework for electronic medical records

## Overview

This repository contains Jupyter notebooks implementing a multi-step feature selection framework for identifying significant variables in electronic medical records (EMR) data for clinical outcome prediction. This framework optimizes the selection process across multiple stages to improve model accuracy, stability, and interpretability. 

The notebooks can be used to reproduce the figures in our paper, as outlined in the table below.

| Notebook                      | Description                                                                                   | Figures                              |
| ----------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------ |
| **1_tableone_fs1.ipynb**      | Data reading, feature distribution, initial feature selection                                 | -                                    |
| **2_fs1_10ml_metrics.ipynb**  | ML model comparison based on initial feature selection                                        | **Figure 2**                         |
| **3_feature_diversity.ipynb** | Feature importance ranking with 6 methods, visualizing differences across methods and samples | **Figure 3**                         |
| **4_fs2_trends.ipynb**        | Analyzes trends in accuracy, similarity, and stability for 6 methods                          | **Figure 4**                         |
| **5_fs2_topk.ipynb**          | Determines optimal top-K values based on accuracy, similarity, and stability trends           | **Supplementary Figures 1 & 2**      |
| **6_fs0123_metrics.ipynb**    | Evaluates performance across four stages of the multi-step feature selection process          | **Figure 5, Supplementary Figure 3** |
| **7_shap_analysis.ipynb**     | SHAP analysis on the final model to interpret feature impact                                  | **Figure 6, Supplementary Figure 4** |

## Data

The project uses the following datasets:

- **MIMIC-III v1.4** (for ICU AKI prediction)
- **MIMIC-IV-ED v2.0** (for ED-to-ICU mortality prediction)

These datasets require credentialed access, and can be downloaded from [PhysioNet](https://physionet.org).

## Contact

Feel free to [contact us](mailto:hongnianwang@gmail.com) or open an issue if you have any questions.