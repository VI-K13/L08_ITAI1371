# Lab 08: Bias-Variance Tradeoff

**Course:** ITAI-1371 – Machine Learning

**Group 1:** Viktoriya Kurmisheva, Tien Manh Nguyen, Zaid Alayedy

## Lab Overview

In this lab, we explored how model complexity affects machine learning performance. We used Polynomial Regression and a synthetic sine-wave dataset to understand underfitting, overfitting, and the bias-variance tradeoff. We also examined learning curves to compare training and cross-validation performance.

## Tasks Completed

**Task 1: Polynomial Regression**
- Created and trained polynomial regression models with degrees 1, 4, and 15.
- Generated predictions and visualized how each model fitted the dataset.
- Compared the models to identify underfitting, overfitting, and a better balance between the two.

**Task 2: Learning Curves**
- Generated learning curves for the degree 1 and degree 15 models.
- Compared training and cross-validation scores as the training size increased.
- Examined how model complexity affects performance on new data.

**Knowledge Check**
- Answered three questions about underfitting, overfitting, and the bias-variance tradeoff.

## Key Takeaways

We learned that increasing model complexity does not always improve performance. The degree 1 model was too simple to capture the pattern, while the degree 15 model was too complex and showed signs of overfitting. The degree 4 model provided a better balance. Learning curves also helped us understand why high training scores do not necessarily mean a model will perform well on new data.

## Files

- **L08_Group1_ITAI1371.ipynb** – Completed Jupyter Notebook containing the code, visualizations, and Knowledge Check answers.
- **L08_Group1_ITAI1371.ipynb - Colab.pdf** – PDF export of the completed notebook, including the code and generated outputs.
- **Reflection Journal (L08Journal_R_Group1_ITAI1371)** – Describes our group's learning experiences, challenges, observations, and understanding of underfitting, overfitting, and the bias-variance tradeoff. It also connects the lab to our previous work in Model Evaluation and discusses questions we would like to explore in future experiments.
- **Team Member Contribution Journal (L08Journal_C_Group1_ITAI1371)** – Documents each group member's responsibilities, including the assigned coding tasks, Knowledge Check questions, notebook review, journal preparation, and GitHub submissions.

## Tools and Libraries

- Python
- Google Colab
- NumPy
- Matplotlib
- Scikit-learn

## Conclusion

This lab helped us understand the importance of choosing an appropriate model complexity and using training and cross-validation results to evaluate how well a model generalizes to new data.
