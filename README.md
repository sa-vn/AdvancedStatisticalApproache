## Implementation Overview

The aim of this project is to explore the application of **Principal Component Analysis (PCA)** for dimensionality reduction. The **star classification dataset** is chosen for analysis. PCA restructures the original dataset into a new space, making the data more manageable and enhancing computational efficiency.

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
