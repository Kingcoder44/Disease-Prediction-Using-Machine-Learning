# Disease Prediction Using Machine Learning

[![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-success?logo=streamlit)](https://future-health-predictor.streamlit.app/)

## Overview

**Future Health Predictor** is a machine learning-based web application that predicts the likelihood of diabetes, heart disease, and Parkinson's disease. The app uses various machine learning algorithms to analyze user input data and provides predictions to assist in early diagnosis.

## Features

- **Diabetes Prediction:** Predicts the likelihood of diabetes based on user input.
- **Heart Disease Prediction:** Analyzes cardiovascular data to predict heart disease risk.
- **Parkinson's Disease Prediction:** Uses vocal and neurological data to assess the risk of Parkinson's disease.
- **User-Friendly Interface:** Built using Streamlit, offering a simple and intuitive interface.

## Technologies Used

- **Python:** Core programming language.
- **Streamlit:** Framework for deploying machine learning models as web applications.
- **Scikit-learn:** Machine learning library for model training.
- **Pickle:** Used for saving and loading trained models.

## Project Structure

- `app.py`: Main application file containing the Streamlit app code.
- `saved_models/`: Directory containing pre-trained models for each disease prediction.
- `requirements.txt`: List of dependencies required to run the app.
- `README.md`: Documentation and instructions for the project.

## Deployment

The app is deployed on Streamlit Cloud and can be accessed [here](https://future-health-predictor.streamlit.app/).

## Installation

To run the application locally, follow these steps:

1. Clone the repository:
    ```bash
   git clone https://github.com/Kingcoder44/Disease-Prediction-Using-Machine-Learning.git
    cd Disease-Prediction-Using-Machine-Learning
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

## Usage

- Open the app using the provided Streamlit Cloud link.
- Select the type of prediction (Diabetes, Heart Disease, Parkinson's Disease) from the sidebar.
- Fill in the required inputs and click on the 'Predict' button.
- The app will display the prediction result.

## Model Information

The project uses the following machine learning models:

- **Diabetes Prediction:** Logistic Regression
- **Heart Disease Prediction:** Random Forest Classifier
- **Parkinson's Disease Prediction:** Support Vector Machine (SVM)

## License

This project is licensed under the MIT License.

## Acknowledgments

- [Streamlit](https://streamlit.io/)
- [Scikit-learn](https://scikit-learn.org/)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) for providing the datasets.

## Contact

For any queries or issues, feel free to open an issue or contact me via email at skushagra645@gmail.com.
