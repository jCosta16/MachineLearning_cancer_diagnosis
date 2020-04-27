# Breast Cancer Diagnosis using Machine Learning

Medical studies use information to support diagnoses and treatments. With each exam generating a substantial amount of data, Machine Learning could be a powerful tool to assist in diagnoses and projections for both doctors and researchers.

In this project our objective is to apply machine learning models to two different data types in order to verify which tool has the highest accuracy in automated cancer classification.

For the image analysis of a Invasive Ductal Carcinoma (IDC), our goal is to create a model that predicts whether the image represents cancerous cells (1) or non-cancerous cells (0). 

For the numerical data, gathered through analysis of a Fine Needle Aspiration (FNA) of a breast mass, the predictor category is benign versus malignant, based on features such as the cell area, smoothness, texture, etc.

Currently, our numeric data classifier has an accuracy of ~96% and our image classifier has an accuracy of 85%.

Data Sets: 
* [Numeric Values - (FNA)](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
* [Image Dataset - (IDC)](https://www.kaggle.com/paultimothymooney/breast-histopathology-images)

## Applied Technologies
* Python
* scikit-learn
* keras
* Matplotlib

## Some Visualizations
### Feature Engineering
![](/images/01_best_features_correlation.png)
![](/images/03_best_features_vs_diagnosis1.png)
### Oversampling
![](/images/08_oversampling_visualization2.png)
### Models
![](/images/11_model_visualization3_GB_EM.png)

