The Crop Recommendation System uses a dataset collected by the Food and Agriculture Council of India containing soil nutrient levels, weather conditions, and other environmental factors. It applies various machine learning models to predict the best crop to plant in a given condition, helping farmers optimize yield and resource usage.

## Dataset

- Source: [Crop Recommendation Dataset on Kaggle](https://www.kaggle.com/datasets/siddharthss/crop-recommendation-dataset?select=Crop_recommendation.csv)
- Size: 2200 samples, 22 crop categories
- Features include:
  - Soil nutrients: Nitrogen (N), Phosphorus (P), Potassium (K)
  - Weather: Temperature, Humidity, Rainfall
  - Soil pH
- Each crop class contains approximately 100 samples.

## Features

- Data preprocessing including:
  - Outlier detection and removal
  - Data scaling/standardization
  - Data augmentation with Gaussian noise to increase training data size
- Machine learning models applied:
  - Decision Trees
  - Random Forest
  - Support Vector Machines (SVM)
  - Gradient Boosting
- Model evaluation using metrics such as:
  - Accuracy
  - Confusion Matrix
  - R², MAE, MSE for regression variants
 
 ## Installation

Clone the repository:

      git clone https://github.com/sekarbharathi/crop-recommendation.git 

## Installation

Run the Jupyter notebook Crop_Recommendation.ipynb to:

Preprocess the data

Train the models

Evaluate performance

Make predictions

## Results
Models were tested using a 60/40 train-test split.

Augmentation with Gaussian noise improved model robustness.

Random Forest and Gradient Boosting models showed the best accuracy in classifying crop types.

Visualizations include boxplots for outlier detection and performance plots for model evaluation.

## Contributors

Alireza Dehghan Nayeri

Bharathi Sekar

Karlo Rosenthal

Usama Raheel





