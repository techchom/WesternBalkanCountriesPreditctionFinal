# Prediction App for Western Balkan Countries

Application Link:
https://population-prediction-for-western-balkan-countries.streamlit.app/

This Streamlit app predicts the population of Western Balkan countries using various machine learning models. The app allows users to select different models and visualize predictions up to the year 2045.

## Features

- Predict population using:
  - Polynomial Regression
  - Linear Regression
  - Support Vector Regression (SVR)
  - Decision Tree Regression
- Visualize predictions with interactive plots.
- Compare model performances using R² score, Mean Absolute Error (MAE), and Mean Squared Error (MSE).
- Styled with a custom CSS theme.

## Installation

To run this app locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/techchom/Prediction-app-for-Western-Balkan-Countries.git
    cd Prediction-app-for-Western-Balkan-Countries
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python -m venv venv
    venv\Scripts\activate  # On Windows
    source venv/bin/activate  # On macOS/Linux
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app:**

    ```bash
    streamlit run Population_App.py
    ```

5. **Access the app in your browser:**

    Once the app is running, you can view it at `http://localhost:8501`.

## Usage

1. Open the app in your browser.
2. Select the desired machine learning model.
3. View the predicted population and model performance metrics.
4. Use the interactive plots to visualize the predictions.

## Deployment

To deploy the app using Streamlit Sharing:

1. Go to [Streamlit Sharing](https://population-prediction-for-western-balkan-countries.streamlit.app/).
2. Connect your GitHub account and select the repository.
3. Follow the instructions to deploy the app.

## Repository Structure

- `Population_App.py`: Main Streamlit app script.
- `requirements.txt`: List of required packages.
- `data/`: Directory containing data files (if any).
- `README.md`: Project documentation.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [Plotly](https://plotly.com/)
- [Scikit-learn](https://scikit-learn.org/)


