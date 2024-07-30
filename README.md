# House Price Prediction Model

## Description
This repository contains a house price prediction model built using various technologies including Flask, HTML, CSS, and linear regression. The model uses data preprocessing, cleaning, scaling, and linear regression techniques to predict house prices based on various features. The model is served through a Flask web application with a user-friendly interface.

## Features
- **Flask Web Application**: The project incorporates a Flask web application, providing a user-friendly interface for predicting house prices. Users can input details such as the number of bedrooms, bathrooms, house size, and zip code to receive a price prediction.
- **Data Preprocessing**: The data preprocessing steps include cleaning, scaling, and feature engineering to ensure the model performs optimally.
- **Linear Regression Model**: The model is a simple linear regression model implemented using Scikit-learn.
- **Model Evaluation**: The model's performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²) score.
- **Interactive Input**: Users can interact with the web application to input house features and get predictions.
- **Clear and Reset**: Easily clear the input fields and start over with new data.
- **Result Display**: Clearly displays the predicted house price based on the input features.

## Installation
To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/sohailshk/House-Price-Prediction.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd House-Price-Prediction
    ```

3. **Create a virtual environment:**
    ```bash
    python -m venv venv
    ```

4. **Activate the virtual environment:**
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

5. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```
## Usage
1. **Run the Flask application:**
    ```bash
    python main.py
    ```
## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or new features.
