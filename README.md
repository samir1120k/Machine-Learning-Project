# Wine Quality Prediction

This project aims to predict the quality of red wine based on various physicochemical properties.

## Dataset

The dataset used in this project is the "winequality-red.csv" dataset. It contains information about various physicochemical properties of red wine, such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, and quality.

## Methodology

1. **Data Loading and Preprocessing:** The dataset is loaded using Pandas and preprocessed by handling missing values and outliers.
2. **Exploratory Data Analysis:** Correlation analysis and data visualization are performed to gain insights into the relationships between different features and the target variable (quality).
3. **Feature Selection:** Relevant features are selected for model training.
4. **Model Training:** A Random Forest Classifier is used to train the prediction model.
5. **Model Evaluation:** The model's performance is evaluated using metrics such as accuracy.
6. **Hyperparameter Tuning:** The model is optimized by tuning hyperparameters to improve its performance.

## Usage

1. **Clone the repository:** `git clone <repository_url>`
2. **Install dependencies:** `pip install -r requirements.txt`
3. **Run the Jupyter Notebook:** `jupyter notebook wine_quality_prediction.ipynb`

## Results

The Random Forest Classifier achieved an accuracy of [insert accuracy score here] on the test set.

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request.

**Link to Colab Notebook**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12cMUowIXzXsxzjaSMSCY_uE3ZdqX1ttO?usp=sharing)
