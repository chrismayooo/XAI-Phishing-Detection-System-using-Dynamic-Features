# XAI Phishing Detection System using Dynamic Temporal Features
**Christopher Mayo**

## Overview
This repository hosts the **Explainable AI (XAI) Phishing Detection System**, developed as part of the research project *"A Dynamic Explainable AI Approach for Phishing Detection Using Temporal-Aware Features with LIME and SHAP"*.

The system explores how **temporal and dynamic features** in email behaviour can enhance phishing detection accuracy while maintaining **transparency and interpretability** through explainable AI methods.

Traditional phishing classifiers often achieve high accuracy but offer limited understanding of *why* a particular email is flagged. This project bridges that gap by integrating **XAI techniques**—notably **SHAP** and **LIME**—to provide human-interpretable insights into model decision-making.

## Research Goal
To design and evaluate a machine learning-based phishing detection system capable of:

- Detecting phishing emails using **dynamic temporal patterns** (e.g., time-dependent sender and content features)
- Explaining classification outcomes for **human analysts and security teams**
- Balancing **performance, interpretability, and practical deployment**

## Key Contributions

- **Novel Dynamic Feature Engineering**: Extracted and analysed time-evolving behavioural indicators from email metadata and content, enabling improved differentiation between legitimate and phishing campaigns
- **Explainability-Driven Evaluation**: Incorporated **SHAP** and **LIME** to visualize model reasoning at both global and local levels, enhancing trust and transparency
- **Comprehensive Model Benchmarking**: Compared algorithms such as **Random Forest**, **XGBoost**, and **Logistic Regression**, highlighting how dynamic features affect interpretability and performance

## Dataset
Dataset sourced from Kaggle: https://www.kaggle.com/datasets/naserabdullahalam/phishing-email-dataset

## Key Insights
Through experimental analysis, the research found that incorporating **temporal dynamics** significantly improves phishing detection models. More importantly, **explainable AI methods exposed how certain behavioural signals**—such as sender repetition patterns, link timing, or content drift—correlate with malicious intent, offering actionable insights for cybersecurity analysts.

## Key Findings
-Money-related features emerged as top phishing indicators via SHAP/LIME analysis.
-Data year signals highlighted temporal attack patterns, boosting model interpretability.
-Visualizations in Lime graphs and Shap bee swarm plots confirm these drive high-confidence detections.
