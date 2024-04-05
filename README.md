# SentimentAnalysis
# Sentiment Analysis Project

## Description
This project implements various deep learning models for sentiment analysis on text data. It includes models such as CNN, LSTM, LSTM with attention mechanism, Bidirectional LSTM, and GRU. The project preprocesses text data, trains the models, evaluates their performance, and provides predictions on new data.

## Dependencies
- Python 3
- TensorFlow
- NLTK
- scikit-learn
- matplotlib
- pandas
- numpy

Install dependencies using:
```bash
pip install -r requirements.txt

Dataset
The dataset used in this project is sourced from Kaggle. It contains labeled text data with sentiments such as positive, negative, and neutral. Preprocessing steps include handling missing values, balancing class distribution, and text preprocessing (e.g., tokenization, stopword removal).

File Structure
main.ipynb: Jupyter Notebook containing the project code.
tokenizer.pickle: Pretrained tokenizer for text data.
Model_M1.h5: Trained CNN model.
Model_LSTM.h5: Trained LSTM model.
Model_LSTM_Attention.h5: Trained LSTM model with attention mechanism.
Model_BiLSTM.h5: Trained Bidirectional LSTM model.
Model_GRU.h5: Trained GRU model.
requirements.txt: List of dependencies.
Training Models
To train the models, run the code in main.ipynb. Make sure to specify the correct file paths for the dataset.

Testing
To test the models on new data, use the provided functions in main.ipynb. Example usage is provided in the notebook.

Results
The models achieve an average accuracy of 85% on the test data. Confusion matrices and accuracy metrics are provided for each model.

Additional Notes
Consider experimenting with different hyperparameters for improved performance.
The dataset may require further preprocessing or augmentation for better results.
Author
Radhey Kedar



This Markdown document should give a clear structure and formatting to your README file.
