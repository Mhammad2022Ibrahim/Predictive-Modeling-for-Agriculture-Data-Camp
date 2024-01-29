# Predictive-Modeling-for-Agriculture-Data-Camp
# Crop Prediction Model

## Project Description
This project involves building a multi-class Logistic Regression model to predict the optimal crop to plant based on soil measurements. The dataset used in this project, `soil_measures.csv`, contains measurements of Nitrogen, Phosphorous, Potassium levels, and pH value of the soil, along with the optimal crop for those soil conditions.

## Features
The dataset contains the following features:
- Nitrogen content ratio in the soil (N)
- Phosphorous content ratio in the soil (P)
- Potassium content ratio in the soil (K)
- pH value of the soil (pH)

## Target Variable
The target variable is the type of crop, which is a categorical variable containing various types of crops.

## Model
The model used in this project is a Logistic Regression model from the sklearn library in Python. The model is trained on two selected features from the dataset to predict the type of crop.

## Performance Metric
The performance of the model is evaluated using the F1 score. The goal is to achieve an F1 score of more than 0.5.

## Files
- `soil_measures.csv`: The dataset file.
- `crop_prediction.py`: The Python script file containing the code for the project.

## Usage
To run the script, you need to have Python installed on your machine along with the necessary libraries such as pandas, sklearn, and seaborn. You can run the script using any Python IDE or from the command line using the command `python crop_prediction.py`.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
MIT
