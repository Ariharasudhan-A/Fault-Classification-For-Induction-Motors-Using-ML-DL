# Fault Classification For Induction Motors Using ML/DL

## Overview

The objective of this project is to classify different types of faults in rotating machinery using both machine learning and deep learning techniques. The classification models are trained on two well-known datasets in fault diagnosis: the **CWRU** and **MFPT** datasets. 

The project involves:
- Data loading, preprocessing, and feature extraction
- Training different ML/DL models
- Implementing an ensemble model for improved performance
- Comparing and evaluating the performance of all models using various metrics

## Datasets

This project uses two datasets:

### 1. **CWRU Dataset**
   The Case Western Reserve University (CWRU) Bearing Data Center dataset includes data for different bearing fault types such as inner race, outer race, and ball faults, with varying fault severities.

   **Link:** [CWRU Bearing Data Center](https://engineering.case.edu/bearingdatacenter/download-data-file)

### 2. **MFPT Dataset**
   The Mechanical Failure Prevention Technology (MFPT) dataset contains vibration data from machinery with normal and faulty conditions, which are used to identify fault types.

   **Link:** [MFPT Dataset](https://www.mfpt.org/fault-data-sets/)

## Models and Performance

The following models are trained and evaluated in this project:

1. **Machine Learning Models:**
   - Random Forest
   - Gradient Boosting
   - Support Vector Machine (SVM)

2. **Deep Learning Models:**
   - Recurrent Neural Network (RNN)
   - Convolutional Neural Network (CNN 1D/2D)
   - Long Short-Term Memory (LSTM) Network

4. **Ensemble Model:**
   - Voting Classifier using RF, GB, RNN, LSTM to improve the overall classification accuracy.

Each model is evaluated based on performance metrics including:
- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1-Score
- AU-ROC Curve

## Results

The notebook provides a detailed comparison of all models trained on both the CWRU and MFPT datasets. The key findings are summarized in the form of tables and plots, comparing performance metrics for each model. The ensemble model achieves the highest performance, achieving the classification accuracy of **97%**.

![image](https://github.com/user-attachments/assets/7b5069ac-6e4b-41e5-89c4-91f5b4e99195)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any queries, feel free to reach out to:
- **Ariharasudhan A** - [Email](mailto:ariadaikalam1234@gmail.com)
