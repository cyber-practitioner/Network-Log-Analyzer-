
---

# Intrusion Detection System

## Overview

This project is an Intrusion Detection System (IDS) built with Django and Python, leveraging machine learning to identify and classify network intrusions. The system preprocesses network traffic data, utilizes machine learning algorithms for prediction, and offers a web interface for interaction and visualization.

## Features

- **Data Preprocessing**: Uses Pandas and Numpy for data cleaning and normalization, including removal of redundant columns and scaling of numerical attributes.
- **Machine Learning Model**: Incorporates a neural network model using Keras for intrusion detection based on preprocessed data.
- **Web Interface**: Django-based web application allowing users to interact with the system, upload data, and view predictions.
- **Feature Selection**: Employs Recursive Feature Elimination (RFE) with RandomForestClassifier for selecting the most significant features from the dataset.

## Getting Started

### Prerequisites

- Python 3.8
- Django
- Pandas, Numpy
- Scikit-learn, Keras

### Installation

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/yourusername/intrusion-detection-system.git
   ```
2. Navigate to the project directory and install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. Run the Django application:
   ```
   python manage.py runserver
   ```

### Usage

After starting the Django development server, navigate to `http://127.0.0.1:8000/` in your web browser to access the IDS interface. You can upload training and testing datasets, view the feature selection process, and see the model's predictions on new data.

## Data Processing and Model Training

The system starts by loading training and testing datasets, followed by data cleaning and normalization. The datasets are then processed to encode categorical attributes and to select the most relevant features. A neural network model is trained with the processed data for intrusion detection.

## Contributing

We welcome contributions to this project. If you have suggestions for improvements or encounter any issues, please feel free to submit an issue or pull request.

---
