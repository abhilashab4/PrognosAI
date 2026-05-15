# PrognosAI

PrognosAI is a machine learning project for predicting the Remaining Useful Life (RUL) of industrial machines using sensor data. The project helps in predictive maintenance by estimating how long a machine can continue operating before failure.

## Features

- Remaining Useful Life prediction
- Streamlit frontend
- Machine learning based prediction
- Sensor data analysis
- Interactive user interface
- Data visualization

## Tech Stack

- Python
- PyTorch
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Dataset

This project uses the NASA CMAPSS (Commercial Modular Aero-Propulsion System Simulation) dataset for Remaining Useful Life prediction.

Dataset includes:

- Engine operational data
- Sensor measurements
- Degradation simulation data
- Remaining Useful Life labels

Dataset source:

[https://data.nasa.gov/dataset/cmapss-jet-engine-simulated-data](https://data.nasa.gov/dataset/cmapss-jet-engine-simulated-data)


## Project Structure

```bash
PrognosAI/
│
├── dataset/                 # Dataset files
├── models/               # Saved models
├── notebooks/            # Jupyter notebooks
├── main.py                # Streamlit frontend
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/abhilashab4/PrognosAI.git
cd PrognosAI
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

Start the Streamlit app:

```bash
streamlit run app.py
```

The app will run at:

```bash
http://localhost:8501
```

## How It Works

1. Load machine sensor data
2. Preprocess and clean the data
3. Train the machine learning model
4. Predict Remaining Useful Life (RUL)
5. Display prediction results in Streamlit

## Future Improvements

- Real-time IoT integration
- Deep learning models
- Cloud deployment
- Live analytics dashboard

## Author

Abhilash A B

GitHub: https://github.com/abhilashab4
