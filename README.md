# Using Machine Learning in Cancer Diagnostics

Medical studies use data to aid in diagnostics and finding appropriate treatment options. With medical exams generating substantial amounts of data, Machine Learning is a powerful tool to assist in diagnostics, for both doctors and medical researchers.

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

## Steps
### Numeric Data
* Step 1 - Feature Selection and Oversampling
  - Using SelectKBest from scikit-learn selected 10 most relevant features from the 32 in the numeric dataset.
  - To improve the slightly imbalance and small data, oversampled the data using the ADASYN model.

* Step 2 - Machine Learn Models and Visualizations
  - Create 5 diferent Machine Learning models to verify the most accurate for the given data.
    . Logistic Regression
    . SVC
    . Neural Network
    . Randon Forest
    . Gradient Boosting
  - Create an Ensemble Vote Classifier aiming to improve the results.
  - Using Matplotlib create visualizations for Feature Selection and Oversampling
  - With the PCA library and Matplotlib create a 2 dimension visualization for the Machine Learn Models.

## Some Visualizations
### Feature Engineering
![](/images/01_best_features_correlation.png)
![](/images/03_best_features_vs_diagnosis1.png)
### Oversampling
![](/images/08_oversampling_visualization2.png)
### Models
![](/images/11_model_visualization3_GB_EM.png)

