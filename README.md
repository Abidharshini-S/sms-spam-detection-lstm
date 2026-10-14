# SMS Spam Detection Using LSTM

## Objective
To classify SMS messages as SPAM or HAM (normal messages) using deep learning.

## Dataset
[Kaggle SMS Spam Detection Dataset](https://www.kaggle.com/datasets/vishakhdapat/sms-spam-detection-dataset)

Approximately 2,000 labelled SMS messages were used.

## Technologies Used
- Python
- Google Colab
- TensorFlow/Keras
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn

## Methodology
1. Load the dataset and handle missing values.
2. Clean and preprocess SMS text.
3. Tokenize messages and pad numerical sequences.
4. Build and train an LSTM model.
5. Evaluate the model using accuracy, precision, recall and F1-score.
6. Display the confusion matrix.
7. Predict unseen SMS messages.

## Results
- Accuracy: 98.5%
- Precision: 94%
- Recall: 94%
- F1-score: 94%

## Confusion Matrix

| Actual | Predicted Ham | Predicted Spam |
|---|---:|---:|
| Ham | 347 | 3 |
| Spam | 3 | 47 |

## How to Run
1. Open the notebook in Google Colab.
2. Upload the Kaggle dataset CSV file.
3. Run the notebook cells in order.
4. Test your own SMS messages.
