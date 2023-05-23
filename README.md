## Machine Learning Final Project - Breast Cancer Classifier

This repository contains the final project for the Machine Learning class. The project focuses on developing a classifier for breast cancer detection, aiming to improve awareness and facilitate early detection of the disease.

### Motivation

Breast cancer is the most common type of cancer in women, with a significant number of cases going undetected during screenings. The goal of this project is to leverage machine learning techniques to develop a classifier that can accurately classify tumors as malignant or benign. By improving the accuracy of classification, we can enhance breast cancer awareness and potentially increase the odds of early detection, leading to improved patient outcomes.

### Methodology

The project followed the following steps:

1. **Data Visualization**: The data was visualized to identify potential correlations and outliers.

2. **Data Cleaning**: Various data cleaning techniques were applied, including handling NaN values and converting text and categorical attributes into numerical form. Feature scaling and transformation pipelines were implemented as necessary, and Principal Component Analysis (PCA) was performed.

3. **Train-Validation Split**: The data was divided into training and validation sets for model training and evaluation.

4. **Classifier Training**: Four classifiers were trained on the data:
   - K-Nearest Neighbors (KNN)
   - Decision Trees
   - Support Vector Machines (SVM)
   - Adaboost

5. **Performance Evaluation**: The performance of each classifier was assessed using cross-validation, and the model with the highest accuracy was selected.

6. **Hyperparameter Tuning**: The hyperparameters of the chosen model were fine-tuned using the Grid Search method.

7. **Test Set Evaluation**: The final model was evaluated on a separate test set to assess its performance.


### Implementation and Analysis

The results of this project have been promising, instilling hope for the future. Breast cancer is a prevalent form of cancer among women, and often, individuals are unaware of the need for regular checkups. Our model achieved a peak average score of 62%, which is comparable to the accuracy of industry-standard mammograms and other tests used to detect malignant tumors. The implementation of this model would be especially impactful if we develop an application that allows users to test their symptoms. With the model's ability to correctly identify a malignant tumor in a patient 8 out of 13 times, we believe that continuous improvement can lead to boundless implementation possibilities.

### Future Work

In future work, our aim is to leverage the information gathered to create an application that can be used by the general public to gain insights into their condition using our model. People may not always have immediate access to their medical records, but they can recognize common symptoms associated with breast cancer. Therefore, we intend to incorporate parameters such as lumps, swelling, or flaky skin into our model to improve its accuracy further. Additionally, collaborating with industry experts in the field of breast cancer will enable us to expand our knowledge and contribute to promoting early screening practices for individuals unaware of the risks.
