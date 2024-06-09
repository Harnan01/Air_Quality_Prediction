
# Air Quality Prediction Project

This project focuses on predicting air quality using machine learning techniques. The project includes data preprocessing, model training, and deployment using a web application interface.

## Project Structure

- `air_quality_model.h5`: Pre-trained model for air quality prediction.
- `AirQualityUCI.xlsx`: Dataset used for training and testing the model.
- `app.py`: Flask application for serving the prediction model.
- `CO326_AirQuality_Project.ipynb`: Jupyter notebook containing the code for data analysis, preprocessing, model training, and evaluation.
- `scaler.pkl`: Pre-trained scaler used for data normalization.
- `streamlit_app.py`: Streamlit application for interactive web-based model predictions.

## Setup Instructions

### Prerequisites

Ensure you have the following installed:
- Python 3.7 or above
- Flask
- Streamlit
- TensorFlow
- Pandas
- Scikit-learn
- Openpyxl

### Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required packages using pip:

```bash
pip install -r requirements.txt
```

### Running the Project

#### Using Flask

1. Navigate to the project directory.
2. Run the Flask application:

```bash
python app.py
```

3. Access the Flask application in your web browser at `http://127.0.0.1:5000`.

#### Using Streamlit

1. Navigate to the project directory.
2. Run the Streamlit application:

```bash
streamlit run streamlit_app.py
```

3. Access the Streamlit application in your web browser at the URL provided in the terminal.

## Project Details

### Data

The dataset used in this project is sourced from the UCI Machine Learning Repository. It contains various features related to air quality measurements.

### Model

The model used for prediction is a neural network trained using TensorFlow and Keras. The input data is normalized using a pre-trained scaler (`scaler.pkl`).

### Web Application

Two web application interfaces are provided:
- `app.py`: A Flask application for serving the model predictions.
- `streamlit_app.py`: A Streamlit application for interactive model predictions.

## Usage

- For Flask: Enter the required input features on the web form and get the predicted air quality.
- For Streamlit: Use the sliders and input fields to enter the features and get real-time predictions.

## Acknowledgements

This project was developed as part of the CO326 course at the University. Special thanks to the course instructors and the UCI Machine Learning Repository for providing the dataset.

## License

This project is licensed under the MIT License.
