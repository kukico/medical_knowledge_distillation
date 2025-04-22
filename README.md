# 🔍 XGBoost-Based Clinical Outcome Prediction with Knowledge Distillation

This repository contains a clean and modular implementation of an **XGBoost-based classifier** with optional **knowledge distillation**, designed for evaluating and improving model performance across different ICU datasets (e.g., MIMIC-III, eICU).

The code supports:
- K-Fold Cross-Validation with ROC & PR curves and CI computation
- Knowledge Distillation from a teacher model
- Model calibration via isotonic regression
- Out-of-distribution evaluation across clinical datasets

---

## 🧠 Background

This implementation is based on the methods presented in the following paper:

**[Insert Paper Title Here]**  
*Authors: [Insert authors]*  
[Insert journal/conference name or arXiv link if available]

The primary goal is to explore how **knowledge distillation (KD)** can improve generalization performance in a clinical outcome prediction model trained on structured EHR data.

---

## 🚀 Features

- ✅ Modular, readable code structure
- ✅ Cross-validation with full evaluation reporting
- ✅ ROC and PR AUC with bootstrap-based confidence intervals
- ✅ Knowledge Distillation (KL + CE hybrid loss)
- ✅ Calibration using `CalibratedClassifierCV`
- ✅ Tested with MIMIC-III and eICU datasets

---

@misc{yourpaper2024,
  title={Knowledge Distillation for Tbi Prognosis: Addressing Feature Mismatch in Heterogeneous Clinical Datasets},
  author={Shuaixun Wang, Martyn G Boutelle},
  year={2024},
  eprint={ssrn:5003367},
  primaryClass={cs.LG}
}


