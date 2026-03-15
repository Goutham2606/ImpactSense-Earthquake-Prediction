# ImpactSense – Earthquake Impact Prediction

## Project Overview
ImpactSense is a machine learning project that predicts the potential impact or risk level of earthquakes using seismic data. The system analyzes features such as magnitude, depth, latitude, and longitude to classify earthquakes into different risk levels.  
This project demonstrates how data science techniques can be applied to real-world geophysical problems. It aims to provide insights that may help in disaster preparedness and early response planning.

## Objective
The goal of this project is to build predictive models that help estimate earthquake impact levels. This can assist in disaster preparedness, infrastructure planning, and emergency response.  
By analyzing historical earthquake data, the model attempts to identify patterns that influence earthquake severity. These predictions can help authorities better understand potential risk zones.

## Dataset
The dataset used in this project was obtained from Kaggle and contains historical earthquake records including magnitude, depth, latitude, and longitude.  
Each row in the dataset represents a recorded earthquake event with its location and seismic measurements. This dataset provides valuable information for understanding earthquake characteristics.

## Features Used
- Magnitude
- Depth
- Latitude
- Longitude

These features represent important seismic and geographic attributes of earthquakes. They help the model understand where an earthquake occurred and how strong it was.

## Target Variable
Risk Level (Low, Medium, High)

The target variable represents the predicted impact level of an earthquake event. It helps categorize earthquakes into understandable risk groups for easier interpretation.

## Risk Level Classification
To predict earthquake impact, magnitude values were converted into risk categories.  
This classification helps simplify raw magnitude values into meaningful categories for machine learning prediction.

| Magnitude Range | Risk Level |
|-----------------|-----------|
| Less than 2.5   | Low       |
| 2.5 – 4.5       | Medium    |
| Greater than 4.5| High      |

## Machine Learning Models Implemented

### Baseline Models
- Logistic Regression
- Decision Tree

These models were implemented as baseline algorithms to understand the initial performance of the dataset. They provide a simple benchmark for evaluating more advanced models.

### Advanced Models
- Random Forest
- Gradient Boosting

These models use ensemble learning techniques to improve prediction accuracy. They combine multiple decision rules to capture complex patterns in earthquake data.

## Model Evaluation
The models were evaluated using the following metrics:

- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

These evaluation metrics help measure how well the models perform on unseen data. They provide insights into the reliability and effectiveness of the prediction system.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook / Google Colab

These tools were used for data preprocessing, model development, and visualization. They provide a powerful environment for building machine learning applications.

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
