## Implementation Overview

This report applies **Principal Component Analysis (PCA)** to reduce the dimensionality of the **star classification dataset**. PCA transforms the original dataset into a new space, simplifying the data and improving computational efficiency.

### Key Findings:
- The first two **principal components** capture the majority of the variance.
- A **scree plot** indicates an elbow at the second component, suggesting an optimal number of components.
- Machine learning models, including **XGBoost, LightGBM, and Gradient Boosting Classifier (GBC)**, are examined for classification performance.
- The **classification performance** before and after PCA transformation is evaluated.

### Results:
- PCA enhances data **interpretability** while maintaining **competitive model performance**.
- **Explainable AI (XAI)** techniques, particularly **Shapley values**, are used to analyze the impact of principal components on model predictions.
- The findings demonstrate PCA’s effectiveness in **simplifying high-dimensional data** and improving model analysis for complex classification tasks.

This implementation provides valuable insights into **dimensionality reduction** and **feature interpretability**, making it useful for real-world classification problems.
