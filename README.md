# BigData Churn predict
<!-- omit in toc -->
## Languages
[![python](https://img.shields.io/badge/python-3.13-d6123c?color=white&labelColor=d6123c&logo=python&logoColor=white)](#)
[![Excel](https://img.shields.io/badge/Excel-Spreadsheet-d6123c?logo=microsoft-excel&logoColor=white&color=white&labelColor=d6123c)](#)

---

<!-- omit in toc -->
## Frameworks
[![numpy](https://img.shields.io/badge/numpy-2.2.6-d6123c?logo=numpy&logoColor=white&color=white&labelColor=d6123c)](#)
[![pandas](https://img.shields.io/badge/pandas-2.2.6-d6123c?logo=pandas&logoColor=white&color=white&labelColor=d6123c)](#)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.6.1-d6123c?logo=scikit-learn&logoColor=white&color=white&labelColor=d6123c)](#)
[![matplotlib](https://img.shields.io/badge/matplotlib-3.10.3-d6123c?color=white&labelColor=d6123c)](#)
[![seaborn](https://img.shields.io/badge/seaborn-0.13.2-d6123c?logo=seaborn&logoColor=white&color=white&labelColor=d6123c)](#)
[![plotly](https://img.shields.io/badge/plotly-6.1.2-d6123c?logo=plotly&logoColor=white&color=white&labelColor=d6123c)](#)
[![catboost](https://img.shields.io/badge/catboost-1.2.8-d6123c?logo=catboost&logoColor=white&color=white&labelColor=d6123c)](#)
[![lightgbm](https://img.shields.io/badge/lightgbm-4.6.0-d6123c?logo=lightgbm&logoColor=white&color=white&labelColor=d6123c)](#)
[![xgboost](https://img.shields.io/badge/xgboost-3.0.2-d6123c?logo=xgboost&logoColor=white&color=white&labelColor=d6123c)](#)
[![optuna](https://img.shields.io/badge/optuna-4.4.0-d6123c?logo=optuna&logoColor=white&color=white&labelColor=d6123c)](#)



---

<!-- omit in toc -->
## Table of Contents
- [Introduction](#introduction)
- [🎯 Project Goals](#-project-goals)
- [📊 Data Description](#-data-description)
- [⚙️ Automatization](#️-automatization)
- [🔬 Research Numbers Dataset](#-research-numbers-dataset)
- [💡 Marketing Strategy](#-marketing-strategy)
- [🏆 Feature Importance](#-feature-importance)
- [📈 Results](#-results)


## Introduction
The final project of [BigDataLab](https://www.bigdatalab.com.ua/) course.

## 🎯 Project Goals

- Identify subscribers who will leave the service in 2 months and interpret the reasons for their churn.
- Achieve model training requirement:  
  **AUC metric ≥ 0.89**

---

## 📊 Data Description

<img src="images/train_raw_TABLES.png" alt="Data description" width="700"/>

---

## ⚙️ Automatization with Excel

- Automated data profiling was performed to identify outliers and missing values.

  <img src="images/automated_data.png" alt="Automated data profiling" width="700"/>

- Model saving and evaluation metrics were automated for quick retrieval.

  <img src="images/models_eval.png" alt="Models evaluation" width="700"/>

---

## 🔬 Research Numbers Dataset

It was hypothesized that customer churn could be influenced by interactions with the following groups of subscribers:
- Microloans and scammers
- Banks
- Competitors
- Vodafone services and support

<img src="images/research.png" alt="Research" width="700"/>

---

## 💡 Marketing Strategy

Passive and aggressive strategies for customer retention were proposed to ensure efficient use of resources.

<img src="images/marketing.png" alt="Marketing" width="700"/>
<img src="images/marketing_distrib.png" alt="Marketing distribution" width="700"/>

---

## 🏆 Feature Importance

<img src="images/feature_import.png" alt="Feature importance" width="700"/>

---

## 📈 Results

- A LightGBM model was designed that effectively distinguishes between subscribers who are likely to churn in 2 months and those who will remain.
- The model identifies more than **70%** of subscribers who are likely to churn.
- Achieved **AUC metric of 0.902 ≥ 0.89**, meeting the task requirement.
- Proposed effective aggressive and passive business strategies for customer retention.
- Investigated key factors influencing customer churn:
  - Customer activity
  - Customer balance
  - Vodafone's market share in the region
  - Bank usage activity
- Found that not all subscribers who churn are worth the cost of retention.
- Discovered that some subscribers churn unexpectedly, regardless of the service.

---

<p align="center">
  <i>Made with ❤️ by BigDataLab students</i>
</p>
