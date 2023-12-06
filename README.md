# Microsoft-Coding-Challenge
# Malware Detection System

## Project Overview
This project aims to detect malware presence in Windows machines using various machine learning models. We explore the effectiveness of Naive Bayes, Random Forest, LightGBM, and neural networks implemented through Keras.

## Dataset
The dataset used is sourced from the Microsoft Malware Prediction competition on Kaggle, which includes a mix of numerical and categorical variables indicative of malware presence.

## Data Preprocessing
Data cleaning and preprocessing involved handling missing values, encoding categorical variables, and addressing class imbalances. The detailed process is documented in the `data_preprocessing` directory.

## Modeling
We experimented with several models:
- `logistic_regression_model.ipynb`
- `random_forest_model.ipynb`
- `lightgbm_model.ipynb`

Each model's performance is evaluated based on accuracy, precision, recall, and F1 score.

## Results
The models' performance varied, with Random Forest and LightGBM showing promising results. Future work may involve model tuning and exploring additional data features.

## Installation
Instructions to set up the project environment are provided in `INSTALL.md`.

## Usage
Each model can be run separately using Jupyter Notebooks. For batch processing, refer to `scripts/run_models.sh`.

## Contributing
Contributions are welcome. Please submit a pull request or create an issue for bugs and feature requests.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
Project Link: [https://github.com/your_username/your_project_name](https://github.com/your_username/your_project_name)
