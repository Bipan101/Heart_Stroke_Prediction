# Heart Disease Prediction App

A simple Streamlit web app that uses a trained logistic regression model to estimate heart disease risk from a small set of clinical inputs.

## Overview

The app loads a pre-trained model, scaler, and expected feature list from the repository and turns user inputs into a prediction in the browser. It is designed to be lightweight and easy to deploy on GitHub and Streamlit Community Cloud.

## Features

- Interactive Streamlit form for entering patient details
- One-click prediction with risk feedback
- Uses the bundled model artifacts in the repo
- Minimal setup for local development and deployment

## Tech Stack

- Python
- Streamlit
- Pandas
- Joblib
- Scikit-learn

## Project Files

- `app.py` - main Streamlit application
- `LogisticRegressionHeart.pkl` - trained classification model
- `scaler.pkl` - fitted feature scaler
- `columns.pkl` - expected model input columns

## Local Setup

1. Create and activate a virtual environment.
2. Install the required packages:

```bash
pip install streamlit pandas joblib scikit-learn
```

3. Run the app:

```bash
streamlit run app.py
```


## Important Note

This app provides an ML-based estimate and is not a medical diagnosis tool. It should not be used as a substitute for professional medical advice.
