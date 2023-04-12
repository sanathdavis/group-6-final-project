### Group 6 

# Boston House Pricing Prediction

This is a Flask web application that predicts the prices of houses in Boston based on input features. The application uses a trained regression model and a scaling object to transform input data and make predictions.

## Getting Started

To run the Boston House Pricing Prediction application, follow these steps:

1. Clone the repository to your local machine.
2. Make sure you have Python 3.x installed on your machine.
3. Install the required libraries by running the following command in the project directory:
 pip install -r requirements.txt

4. Place the trained regression model and scaling object files (`reg_model.pkl` and `scaler.pkl`) in the same directory as the Flask application file.
5. Run the Flask application by running the following command in the project directory:

python app.py

6. Access the application in your web browser by navigating to `http://127.0.0.1:5000/`.

## Usage

Once the Flask application is running, you can access the Boston House Pricing Prediction application through your web browser. The application provides two ways to make predictions:

1. **API Prediction**: You can make predictions using the `/predict_api` endpoint by sending a POST request with input data in JSON format. The input data should contain the following features: `CRIM`, `ZN`, `INDUS`, `CHAS`, `NOX`, `RM`, `AGE`, `DIS`, `RAD`, `TAX`, `PTRATIO`, and `B`. The response will contain the predicted house price in JSON format.

2. **Web Form Prediction**: You can also make predictions using the web form provided on the home page of the application. Enter the values for the input features in the form, and click the "Predict" button. The predicted house price will be displayed on the page.

## Technology Stack

- Python 3.x
- Flask
- NumPy
- Pandas
- Scikit-learn

## License

This project is licensed under the MIT License. Feel free to use and modify the code for your own purposes. Refer to the LICENSE file for more details.

## Disclaimer

This application is for educational and demonstration purposes only. The predicted house prices are based on a trained regression model and may not reflect the actual market prices. Use the application at your own risk.

