Link:-https://startup-prediction.onrender.com/

Of course, here is a comprehensive README file with instructions on how to run the project.

-----

# Startup Success Prediction

This project is a web application that predicts the success of a startup based on various features. It uses a machine learning model trained on a dataset of startup information. The web application is built with **Flask** and allows users to input startup data and get a prediction on its success probability.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

  * **Python 3.10**
  * **pip** (Python package installer)

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/nilashishde/startup-prediction.git
    cd startup-prediction
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the web application, execute the following command in the project's root directory:

```bash
flask run
```

The application will start on `http://127.0.0.1:5000`. Open this URL in your web browser to use the application.

## Model Training

The machine learning model is pre-trained and included in the repository as `model.pkl`. If you wish to retrain the model, you can run the `eda_preprocess_train.py` script.

This script will:

1.  Load the dataset from `startup data.csv`.
2.  Preprocess the data.
3.  Train a new XGBoost model.
4.  Save the new model, scaler, and features to disk.

To run the training script, execute:

```bash
python eda_preprocess_train.py
```
