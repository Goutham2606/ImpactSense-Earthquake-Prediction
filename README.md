# ImpactSense – Earthquake Impact Prediction

## Project Overview
ImpactSense is a machine learning project that predicts the potential impact or risk level of earthquakes using seismic data. The system analyzes features such as magnitude, depth, latitude, and longitude to classify earthquakes into different risk levels.

## Objective
The goal of this project is to build predictive models that help estimate earthquake impact levels. This can assist in disaster preparedness, infrastructure planning, and emergency response.

## Dataset
The dataset used in this project was obtained from Kaggle and contains historical earthquake records including magnitude, depth, latitude, and longitude.

## Features Used
- Magnitude
- Depth
- Latitude
- Longitude

## Target Variable
Risk Level (Low, Medium, High)

## Risk Level Classification
To predict earthquake impact, magnitude values were converted into risk categories.

| Magnitude Range | Risk Level |
|-----------------|-----------|
| Less than 2.5   | Low       |
| 2.5 – 4.5       | Medium    |
| Greater than 4.5| High      |

## Machine Learning Models Implemented

### Baseline Models
- Logistic Regression
- Decision Tree

### Advanced Models
- Random Forest
- Gradient Boosting

## Model Evaluation
The models were evaluated using the following metrics:

- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

These metrics help measure the performance and reliability of the prediction models.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook / Google Colab

## Project Structure
ImpactSense-Earthquake-Prediction
│
├── milestone2_model_training.ipynb  
├── milestone2_documentation.pdf  
├── earthquake_1995-2023.csv  
└── README.md 

## Future Improvements
Future improvements may include:

- Hyperparameter tuning for better accuracy
- Feature importance analysis
- Integration with real-time earthquake data
- Building a user interface for predictions
