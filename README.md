# Mediwhale Data Scientist Assignment: Diabetes Prediction and Analysis

## Project Description
This project provides a Streamlit-based dashboard for diabetes prediction and analysis using the National Health Interview Survey (NHIS) 2018 dataset. The dashboard allows users to explore the dataset, perform feature engineering, train models, and compare the performance of Decision Tree and Logistic Regression models in each pages.


## Features
- **Exploratory Data Analysis**: Visualize and understand the dataset with summary statistics, missing value analysis, and correlation matrices.
- **Data Preparation & Feature Engineering**: Select features, handle missing values, and prepare the dataset for model training.
- **Model Training & Evaluation**: Train Decision Tree or Logistic Regression models, evaluate their performance, and view feature importances.
- **Statistical Model Comparison**: Compare the performance metrics of the trained models to determine the best-performing model.

## How to Use
1. **Load the .tar file with Docker Image:**
   ```
     docker load -i streamlit-app.tar
   ```
2. Verify Docker image:
   ```
   docker images
   ```
   Check if streamlit-app:latest appears

3. Run the Container:
   ```
   docker run -p 8501:8501 streamlit-app:latest
   ```
   The app should now be accessible at http://localhost:8501 in a web browser.
