# Regrespresso

<img width="1024" height="1024" alt="regrespresso_logo" src="https://github.com/user-attachments/assets/47f8de6b-36c9-4679-b2c2-d285d804ab9a" />

### Predicting California Housing Prices (Hands-On Machine Learning, Chapter 2)

---

## Overview

**Regrespresso** is an educational project based on [**Chapter 2: "End-to-End Machine Learning Project"** from *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow* by **Aurélien Géron** (O’Reilly, 3rd Edition)](https://github.com/ageron/handson-ml3).

The objective is to predict **median house values** in California districts using the **California Housing dataset**.  
This repository combines:
- Implementations inspired by the textbook,
- Additional explanations and notes written during study,
- Supplementary insights derived from LLM-based clarifications.

The purpose of this work is purely **educational**—to reinforce understanding of end-to-end machine learning workflows.

---

## Contents and Key Concepts

The project demonstrates a complete workflow for a supervised learning task, including:

- **Data Acquisition and Loading**
  - Using `urllib.request`, `tarfile`, and `pandas` to load the dataset.
- **Exploratory Data Analysis (EDA)**
  - Attribute summaries (`info()`, `describe()`)
  - Handling missing values and non-numeric data
  - Understanding attribute distributions and percentiles
- **Data Visualization**
  - Histograms for distribution analysis
  - Identifying skewed data and scaling needs
- **Data Splitting and Leakage Prevention**
  - Random and deterministic train/test splits
  - Hash-based splitting using `crc32` for reproducibility
  - Discussion of data leakage and dataset version consistency
- **Foundational ML Practices**
  - Bias from capped target values
  - Importance of early test-set creation
  - Dataset stability and identifier-based partitioning

---

## Dataset

**Source:** [California Housing dataset](https://github.com/ageron/data/raw/main/housing.tgz)  
**Attributes:** Median income, total rooms, population, ocean proximity, and others  
**Target:** `median_house_value`


