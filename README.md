# Student Enrollment and Graduation Prediction

## Overview

This project aims to predict student enrollment and graduation success based on historical student enrollment data, academic records, and demographic data..

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Running the Code](#running-the-code)
- [Code Structure](#code-structure)
- [Data](#data)
- [Model Evaluation](#model-evaluation)
- [Visualizations](#visualizations)
- [Saved Model](#saved-model)


## Setup

### Prerequisites

Ensure you have the following software installed:

- Python (>=3.6)
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

### Installation

Install the required dependencies using the following command:

```bash
pip install pandas scikit-learn matplotlib seaborn joblib
```

## Usage

### Running the Code

1. Clone the repository:

```bash
git clone https://github.com/TheODDYSEY/Student-Perfomance-Model
cd Student-Performance-Model
```

2. Run the Python script:

```bash
python model_code.py
```

## Code Structure

- `model_code.py`: The main script containing the machine learning model training, evaluation, and visualization code.
- `enrollment_model.pkl`: The serialized RandomForestClassifier model saved for future use.
- `graduation_model.pkl` :The serialized model for future use

## Data

The sample data used for model training is provided in the script as a hardcoded string. For real-world scenarios, replace this data with your dataset in CSV or Excel format.

## Model Evaluation

The script outputs the following:

- Confusion matrix
- Classification report

## Visualizations

The script generates visualizations:

- Confusion matrix heatmap


## Saved Model

The trained model is saved as `enrollment_model.pkl` and `graduation_model.pkl` for future use.



