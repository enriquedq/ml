# AWS Machine Learning Toolkit and Templates

This repository is a comprehensive collection of Machine Learning templates and implementations designed for scalability and production-readiness. It covers the end-to-end ML lifecycle, from data preprocessing to advanced Deep Learning and Reinforcement Learning models.

Developed as part of my continuous technical evolution and MSc in Data Analytics, these templates serve as a foundation for building robust, "battle-tested" AI solutions on cloud environments (AWS/Azure).

## Repository Structure

The project is organized by ML domains to facilitate quick access and modular integration:

*   **DP (Data Preprocessing):** Foundations for data cleaning, feature scaling, and categorical encoding.
*   **Regression:** Implementation of linear, polynomial, and support vector regression models.
*   **Classification:** A wide array of classifiers including Decision Trees (DTC), KNN, SVM, Naive Bayes, and Random Forest.
*   **Clustering:** Unsupervised learning patterns (K-Means, Hierarchical).
*   **ARL (Association Rule Learning):** Eclat and Apriori implementations.
*   **RL (Reinforcement Learning):** Upper Confidence Bound (UCB) and Thompson Sampling.
*   **NLP:** Natural Language Processing pipelines for text classification and sentiment analysis.
*   **DL (Deep Learning):** Neural Network architectures (ANN, CNN).
*   **DR (Dimensionality Reduction):** PCA, LDA, and Kernel PCA techniques.
*   **Model Selection and Boosting:** Advanced techniques like XGBoost and K-Fold Cross Validation.

## Key Technical Features

*   **Modular Code:** Scripts are designed to be easily adapted to different datasets with minimal configuration.
*   **Scikit-Learn Standard:** Heavy use of industry-standard libraries ensuring compatibility with most production pipelines.
*   **Integrated Preprocessing:** Every classification and regression template includes proper feature scaling and train/test splitting.
*   **Cloud Ready:** Optimized for execution in environments like AWS SageMaker or Azure ML Studio.

## Usage

Each folder contains a standalone Python script and, in some cases, a sample dataset (.csv) for immediate testing. 

Example for Decision Tree Classification:
```python
# Navigate to Classification/DTC
# Run the script:
python decision_tree_classification.py