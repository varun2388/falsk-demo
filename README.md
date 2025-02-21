# Flask Machine Learning Model

This repository contains a Flask application that builds a machine learning model and provides a web interface for making predictions.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- pandas
- scikit-learn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/varun2388/falsk-demo.git
   cd flask-demo
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

1. Start the Flask application:
   ```bash
   python app.py
   ```

2. Open your web browser and go to `http://127.0.0.1:5000/`.

### Usage

- Enter the required features in the form and click the "Predict" button to get the prediction result.

## Machine Learning Model

The machine learning model used in this application is a linear regression model. The model is trained on a dataset containing multiple features and a target variable.

### Dataset

The dataset used for training the model is located in the `data` directory. The dataset contains the following columns:

- `feature1`: Description of feature 1
- `feature2`: Description of feature 2
- `feature3`: Description of feature 3
- `target`: Description of the target variable

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
