# SMS Spam Detection with SVM

This project demonstrates how to build a spam detection model using Support Vector Machines (SVM) and TF-IDF (Term Frequency-Inverse Document Frequency) for feature extraction. 

## Dataset

The project utilizes the "SMS Spam Collection" dataset from the UCI Machine Learning Repository. This dataset contains a collection of SMS messages labeled as either "spam" or "ham" (legitimate).

## Methodology

1. **Data Loading and Cleaning:**
   - The dataset is downloaded and loaded into a pandas DataFrame.
   - Text cleaning is performed to remove special characters, extra spaces, convert text to lowercase, and remove digits.

2. **Feature Extraction:**
   - TF-IDF is used to convert the text data into numerical vectors.
   - `TfidfVectorizer` is used to create a vocabulary of words and assign weights to them based on their frequency in the documents and the corpus.

3. **Model Training:**
   - The dataset is split into training and testing sets.
   - A linear SVM model is trained using the training data.

4. **Model Evaluation:**
   - The trained model is used to predict the labels of the test data.
   - The model's performance is evaluated using metrics like classification report and confusion matrix.

5. **Prediction:**
   - A function `predict_spam` is defined to classify new messages as spam or ham.


## Usage

1. **Clone the repository:**
2. **Install dependencies:**
3. **Run the notebook:**
   Open the `sms_spam_detection.ipynb` notebook in Google Colab or Jupyter Notebook and execute the cells.

## Results

The model achieves high accuracy in classifying spam and ham messages. Refer to the notebook for the detailed classification report and confusion matrix.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests.

## License

This project is licensed under the MIT License.
