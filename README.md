# Titanic Survival Prediction Model

## Project Overview
This machine learning project predicts passenger survival on the Titanic using various classification algorithms and data analysis techniques.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Model Performance](#model-performance)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ranjnisingh8/Titanic-Disaster-Prediction-Model.git
cd Titanic-Disaster-Prediction-Model
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

## Dataset
The project uses the classic Titanic dataset from Kaggle, which contains information about passengers including:
- Survival status
- Passenger class
- Name
- Sex
- Age
- Siblings/Spouses aboard
- Parents/Children aboard
- Ticket fare
- Cabin information
- Embarkation point

## Dependencies
- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter notebook

## Model Performance
The project explores multiple classification algorithms:
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- Decision Tree Classifier

Typical performance metrics include:
- Accuracy
- Precision
- Recall
- F1 Score

## Usage

### Jupyter Notebook
Open the Jupyter Notebook to explore the data and model:
```bash
jupyter notebook classifier.ipynb
```


## Project Structure
```
Titanic-Disaster-Prediction-Model/
│
├── classifier.ipynb      # Main Jupyter Notebook
├── train.csv             # Training dataset
├── test.csv              # Test dataset
└── README.md             # Project documentation
```

## License
Distributed under the MIT License. See `LICENSE` for more information.

