
# Breast Cancer Dataset Comprehensive Analysis

This repository contains a comprehensive analysis of the Breast Cancer dataset. The dataset includes information on patients diagnosed with breast cancer, with attributes such as tumor size, type, location, and clinical outcomes. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, model development, and model evaluation.

## Table of Contents

- [Breast Cancer Dataset Advanced Analysis](#breast-cancer-dataset-advanced-analysis)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Dataset](#dataset)
  - [Analysis](#analysis)
    - [Data Cleaning](#data-cleaning)
    - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
    - [Feature Engineering](#feature-engineering)
    - [Model Development](#model-development)
    - [Model Evaluation](#model-evaluation)
  - [Conclusion](#conclusion)
  - [Requirements](#requirements)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)

## Introduction

This notebook provides a comprehensive analysis of the Breast Cancer dataset. The goal is to develop predictive models and treatment protocols aimed at improving breast cancer management and patient outcomes.

## Dataset

The Breast Cancer dataset includes comprehensive information on patients diagnosed with breast cancer, encompassing demographic data, tumor attributes (size, type, location), and clinical outcomes.

## Analysis

### Data Cleaning

- Handling missing values by dropping columns with all missing values and filling remaining missing values with the mean for numeric columns.

### Exploratory Data Analysis (EDA)

- Distribution of diagnosis
- Pairplot for selected features
- Heatmap of the correlation matrix for numeric columns

### Feature Engineering

- Creation of new features based on existing ones to improve model performance

### Model Development

- Split the data into training and testing sets
- Standardize the features
- Train a Random Forest Classifier
- Make predictions

### Model Evaluation

- Confusion matrix
- Classification report
- Feature importance analysis

## Conclusion

This analysis provides valuable insights into the factors affecting breast cancer prognosis and demonstrates the development and evaluation of a predictive model.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/debjit-mandal/Breast-Cancer-Analysis.git
   cd Breast-Cancer-Analysis
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Notebook**:
   Open the `Advanced_Breast_Cancer_Analysis.ipynb` notebook using Jupyter Notebook and run the cells to reproduce the analysis.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the Boost Software License 1.0 - see the [LICENSE](LICENSE) file for details.
