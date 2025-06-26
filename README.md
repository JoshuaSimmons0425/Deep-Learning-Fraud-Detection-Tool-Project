# About the Project

This project is a deep learning-based financial fraud detection system, designed to accurately identify fraudulent transactions in a structured dataset. The goal is to maximise recall while preserving a reasonable precision, ensuring that most fraudulent transactions are caught with minimal false positives.

Built with a focus on real-world applicability, the project demonstrates key techniques in preprocessing, model training, performance optimization, and explainability, all aligned with the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework.

# Project Goal

- Objective: Accurately detect fraudulent financial transactions using supervised machine learning.
- Key Metric: Prioritise high recall to minimize undetected fraud cases, while maintaining acceptable precision to avoid too many false alarms.
- Challenge: Handle high class imbalance (fraudulent vs. non-fraudulent cases) effectively through weight penalty and model tuning.

# Tools & Libraries Used

- Python (NumPy, pandas, matplotlib, seaborn)
- Scikit-learn for model training and evaluation
- PyTorch for deep learning (neural network modeling)
- Matplotlib/Seaborn for visualizing evaluation metrics

# Techniques & Features

Exploretory Data Analysis

- Class Occurances Visualization using a Histogram 
- Summary statistics to evaulate the distributions and proporties of each feature
- Boxplots & Histograms to examine distribution and detect outliers

Data Preparation and Prepocessing:

Feature construction using:
- Transactional balance changes (e.g., newBalanceOrigin - oldBalanceOrigin)
- Absolute and relative differences

Missing value detection and population using:
- Mode to populate a discrete value in a categorical feature
- Mean to populate a continous value in a numerical feature

Modelling:

- Neural network with weighted loss (to counter class imbalance)
- Threshold tuning to optimize recall/precision tradeoff

Evaluation: 

- Confusion matrix
- Precision-Recall tradeoff graph
- F1-score, precision and recall values
- Model comparison using performance metrics under various thresholds

# CRISP-DM Methodology in Practice

| Phase                         | Implementation                                                                      |
| ----------------------------- | ----------------------------------------------------------------------------------- |
| **1. Business Understanding** | Define objective to reduce undetected fraud in financial systems                    |
| **2. Data Understanding**     | Explore class and feature distribution, correlation, transaction types              |
| **3. Data Preparation**       | Feature engineering, scaling, outlier removal, and handling imbalance               |
| **4. Modeling**               | Train multiple ML models, tune hyperparameters, and evaluate using cross-validation |
| **5. Evaluation**             | Compare models using recall, precision, F1, and interpretability techniques         |
| **6. Deployment (optional)**  | Prepare model for integration into real-time fraud detection pipeline (future goal) |

# Final Notes

This project reflects a holistic and responsible approach to AI in finance, combining domain-relevant feature engineering, balanced model optimization, and interpretable outputs—all underpinned by CRISP-DM methodology. Contributions and feedback are welcome!
