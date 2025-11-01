Overview :
This project focuses on optimizing Machine Learning (ML) and Deep Learning (DL) models for automated ECG (Electrocardiogram) signal analysis, enabling early detection of cardiovascular diseases.
Using the MIT-BIH Arrhythmia Database, the study explores both feature-based and sequence-based approaches, improving accuracy, interpretability, and robustness of ECG classification systems.

Technologies Used :
1) Languages: Python.
2) Libraries: NumPy, Pandas, Scikit-learn, TensorFlow, XGBoost, Matplotlib, PyWavelets.
3) Tools: Jupyter Notebook.

Objectives :
1) Automate ECG signal classification for cardiovascular diagnosis.
2) Extract time-domain, frequency-domain, and wavelet-based features from ECG signals.
3) Compare ML and DL models (Random Forest, XGBoost, LSTM) for optimal performance.
4) Address dataset imbalance using SMOTEENN.
5) Apply Explainable AI (XAI) tools (SHAP, Permutation Importance) for interpretability.
6) Develop an efficient and deployable model for real-time and wearable health monitoring systems.

Key Contributions:

1) Integration of Discrete Wavelet Transform (DWT), Fast Fourier Transform (FFT), and Time Division Analysis for rich feature extraction.
2) Hybrid SMOTEENN technique to balance imbalanced ECG data.
3) Comparative study of Random Forest, XGBoost (with JADE optimization), and LSTM architectures.
4) Use of Explainable AI (SHAP & Permutation Importance) to enhance transparency and clinical trust.
5) Achieved 97.67% accuracy using LSTM and 96.13% with XGBoost on imbalanced data.

Results:

| Technique                  | Accuracy   | Precision | Recall | F1-Score |
| -------------------------- | ---------- | --------- | ------ | -------- |
| LSTM                       | **97.67%** | 97.6%     | 97.67% | 97.58%   |
| Random Forest (Balanced)   | 94.29%     | 95%       | 94%    | 94%      |
| XGBoost (Balanced)         | 91.44%     | 94%       | 91%    | 92%      |
| Random Forest (Imbalanced) | 95.35%     | 95%       | 95%    | 95%      |
| XGBoost (Imbalanced)       | **96.13%** | 96%       | 96%    | 96%      |
