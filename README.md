# IPL Score Prediction

This project aims to predict the total score in an Indian Premier League (IPL) cricket match using machine learning.

## Project Overview

The project utilizes historical IPL data to train a neural network model for predicting the total runs scored in a match. It leverages various features such as venue, batting team, bowling team, batsman, and bowler to make predictions.

## Dataset

The dataset used for this project is `ipl_data.csv`, which contains historical IPL match data. It includes information about various match parameters and outcomes.

## Methodology

1. **Data Preprocessing:**
   - Irrelevant features are removed from the dataset.
   - Categorical features like venue, batting team, and bowling team are encoded using Label Encoding.
   - Data is scaled using MinMaxScaler to ensure consistent feature ranges.

2. **Model Building:**
   - A neural network model is built using Keras with dense layers and ReLU activation functions.
   - The Huber loss function is used for model optimization.
   - The Adam optimizer is employed for training.

3. **Model Evaluation:**
   - The model is evaluated using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2).

4. **Prediction:**
   - An interactive prediction interface is provided using IPython widgets, allowing users to input match parameters and obtain score predictions.

## Usage

1. Clone the repository: `git clone <repository_url>`
2. Install the necessary libraries: `pip install -r requirements.txt`
3. Run the Jupyter Notebook: `jupyter notebook IPL_Score_Prediction.ipynb`
4. Interact with the prediction interface to obtain score predictions.

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow
- Scikit-learn
- Keras
- IPython widgets

## Contributing

Contributions to this project are welcome. Feel free to open issues or pull requests for any improvements or bug fixes.

## License

This project is licensed under the MIT License.
