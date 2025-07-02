# About the Project

This project is a deep learning-based financial fraud detection system, designed to accurately identify fraudulent transactions in a structured dataset. The goal is to maximise recall while preserving a reasonable precision, ensuring that most fraudulent transactions are caught with minimal false positives.

Built with a focus on real-world applicability, the project demonstrates key techniques in preprocessing, model training, performance optimization and evaluation; all aligned with the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework.

The dataset I chose came from Kaggle. Here is the link to the dataset: https://www.kaggle.com/code/kartik2khandelwal/predicting-fraudulent-transactions/input

# Project Goal

- Objective: Accurately detect fraudulent financial transactions using supervised machine learning with a neural network model.
- Key Metric: Prioritise high recall to minimise undetected fraud cases, while maintaining acceptable precision to avoid too many false alarms.
- Challenge: Handle high class imbalance (fraudulent vs. non-fraudulent cases) effectively through weight penalty and model tuning.

# Tools & Libraries Used

- Python (NumPy, pandas, matplotlib, seaborn)
- Scikit-learn for model training and evaluation
- PyTorch for deep learning (neural network modeling)
- Matplotlib/Seaborn for visualizing evaluation metrics

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

This project reflects a holistic and responsible approach to AI in finance, combining domain-relevant feature engineering, balanced model optimization, and interpretable outputs—all underpinned by CRISP-DM methodology. Feedback of any kind are welcome!
