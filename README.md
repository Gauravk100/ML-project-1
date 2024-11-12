# Algerian Forest Fires Prediction Project

## Description

This machine learning project uses regression techniques to predict forest fire occurrences in Algeria based on various environmental features. The model is trained on the Algerian Forest Fires Dataset, utilizing Python libraries such as pandas, scikit-learn, matplotlib, numpy, seaborn, and flask for data analysis, visualization, and model deployment.

## Dataset

Name: Algerian Forest Fires Dataset
Description: The dataset includes information on forest fire occurrences in Algeria, with various environmental factors such as temperature, humidity, wind speed, and more.
Source: UCI Machine Learning Repository

## Libraries and Requirements

This project uses the following libraries:

1. pandas for data manipulation
2. numpy for numerical computations
3. scikit-learn for machine learning models and evaluation
4. matplotlib and seaborn for data visualization
5. flask for creating a web application to serve predictions

To install all required packages, run:
```
pip install pandas numpy scikit-learn matplotlib seaborn flask
```

## Getting Started

1. Clone the repository:

```
git clone https://github.com/your-username/forest-fire-prediction.git
cd forest-fire-prediction
```
2. Load and Explore the Data:

    Explore the dataset using Jupyter notebooks in the notebooks/ folder for a better understanding of features, correlations, and data preparation.

3. Train the Model:

    The notebooks contain steps for feature engineering and model training using regression algorithms. Experiment with different regression models to improve prediction accuracy.

4. Run the Flask App:

    Once the model is trained, you can deploy it using the Flask application. To start the Flask server, run:

```
python app.py

```


  This will launch the application locally, where you can send data through the API and receive predictions.

5. Access the Web Interface:

    Open your web browser and go to http://127.0.0.1:5000/ to access the frontend interface for forest fire prediction.

# Usage Example

API Example

  To use the API, send a POST request with the relevant environmental data in JSON format to http://127.0.0.1:5000/predict.

```
{
  "temperature": 25,
  "humidity": 40,
  "wind_speed": 5,
  "rain": 0,
  "area": 0.5
}
```

The response will contain a prediction of the forest fire risk based on the input data.

Web Interface Example
Use the web form on the main page to input environmental data and receive a forest fire risk prediction directly.

# Results and Visualizations
Visualizations of data correlations, regression model performance, and feature importance are available in the Jupyter notebooks. They provide insights into the model's accuracy and the key factors influencing predictions.
