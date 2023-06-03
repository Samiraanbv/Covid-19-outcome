# Covid-19-outcome
Covid-19 outcome prediction
COVID-19 Outcome Prediction System
## Background

Early prediction of the outcome situation of COVID-19 patients is essential in reducing mortality risk by ensuring efficient resource allocation and treatment planning. This repository presents a highly accurate and fast system for predicting COVID-19 outcomes using demographic, vital signs, and laboratory blood test data.
## Methods

In this analytic study conducted from May 2020 to June 2021 in Tehran, we collected data from 244 COVID-19 patients admitted to Masih Daneshvari Hospital. On the first day of admission, we recorded 41 features, which were categorized into eight different groups: demographic and patient history features, vital signs, and six different groups of laboratory blood tests, including complete blood count (CBC), coagulation, kidney, liver, blood gas, and general. We evaluated the significance of each extracted feature and the eight feature groups separately for predicting mortality outcomes. The statistical methods employed for evaluation included the area under the receiver operating characteristic curve (AUC-ROC) based on the binary Logistic Regression classification algorithm.
## Results

Our analysis revealed significant findings regarding the predictive power of various features and feature groups. The CBC features, specifically red cell distribution width (RDW), mean corpuscular hemoglobin (MCH), mean corpuscular hemoglobin concentration (MCHC), and mean corpuscular volume (MCV), achieved the highest AUC values of 85.29, 80.96, 79.94, and 79.70, respectively. Among the vital features, blood oxygen saturation level (SPO2) exhibited a higher AUC value of 79.28. Combinations of features within the CBC group demonstrated the highest AUC value of 95.57, while the coagulation and vital signs groups achieved AUC values of 85.20 and 83.84, respectively. Notably, the triple combination of features from the CBC, vital signs, and coagulation groups yielded the highest AUC value of 96.54.
## Conclusion

The proposed system can serve as a valuable tool for assisting in the triage of COVID-19 patients, providing insights into their risk for hospitalization and intensive care. By leveraging demographic, vital signs, and laboratory blood test data, our system offers a reliable and efficient means of predicting COVID-19 outcomes. This can aid in optimal resource allocation and treatment planning in medical environments.
## Getting Started

To utilize this COVID-19 outcome prediction system, please follow the steps below:

    . Clone the repository to your local machine.
    . Install the required dependencies outlined in the 'requirements.txt' file.
    . Prepare your dataset with the necessary demographic, vital signs, and laboratory blood test features for input.
    . Use the provided scripts or notebooks to preprocess and analyze the data, applying the appropriate statistical methods and machine learning algorithms.
    . Evaluate the predictive performance of the system using relevant metrics such as AUC-ROC.
    . Customize and fine-tune the system according to your specific needs and datasets.

Please refer to the documentation and code comments for detailed instructions on how to use the system effectively.
Contribution

Contributions to this project are welcome. If you find any issues, have suggestions for improvements, or would like to add new features, please submit a pull request. Let's collaborate to enhance the accuracy and efficiency of COVID-19 outcome prediction.
