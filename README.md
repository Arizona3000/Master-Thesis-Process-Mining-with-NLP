# Integrating Textual Semantics and Explainable AI in Predictive Process Monitoring

This repository contains the research framework and implementation developed as part of my Master Thesis at **ESCP Business School** (MSc in Big Data & Business Analytics, Class of 2025). The project explores how textual semantics and explainable artificial intelligence can be integrated within predictive process monitoring to enhance both predictive performance and interpretability.

The study is based on the **BPI Challenge 2018 event log**, documenting agricultural subsidy applications processed by a Dutch public agency. The research introduces a multimodal pipeline that combines structured numerical and categorical features with unstructured textual attributes, represented through TF-IDF and latent semantic decomposition. Three predictive models are implemented: a numeric-only model, a text-only model, and a combined multimodal model. Random Forest and Logistic Regression classifiers are used to compare predictive accuracy and interpretability.

Explainability is treated as a methodological pillar of the framework. **Local Interpretable Model-Agnostic Explanations (LIME)** and **SHapley Additive exPlanations (SHAP)** are employed to analyze the influence of individual features, both globally and at the case level. These techniques allow a transparent interpretation of model behavior, linking algorithmic outcomes to process semantics and managerial reasoning.

The results demonstrate that textual information substantially improves inefficiency and non-compliance detection while providing an interpretable understanding of process behavior. The combined model offers the most balanced trade-off between accuracy and transparency, confirming that predictive process mining gains explanatory depth when structured and unstructured data are modeled together.

All analyses are implemented in **Python 3.10** using open-source libraries, including `pandas`, `scikit-learn`, `pm4py`, `shap`, and `lime`. The repository reproduces the full experimental workflow described in the thesis, ensuring methodological transparency, reproducibility, and academic integri
