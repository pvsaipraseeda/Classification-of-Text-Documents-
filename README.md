# Text Classification Using Naive Bayes

## About

This project uses Natural Language Processing (NLP) and the Multinomial Naive Bayes algorithm to classify text documents into four categories: Technology, Sports, Politics, and Entertainment.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Workflow

1. Load and explore the dataset.
2. Check and handle missing values.
3. Split the dataset into training and testing sets.
4. Convert text into numerical features using CountVectorizer.
5. Train a Multinomial Naive Bayes classifier.
6. Predict categories for unseen text.
7. Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.

## Algorithm

Multinomial Naive Bayes

## Dataset

- File: `synthetic_text_data.csv`
- Categories: Technology, Sports, Politics, and Entertainment.
- Dataset source and license: To be added.

## Results

The original experiment reported an accuracy of approximately 88.24%.

The accuracy and other evaluation metrics will be updated after running the improved implementation.

## Example Prediction

Input: "I love artificial intelligence and machine learning"

Expected category: Technology

The actual prediction depends on the trained model.

## How to Run

1. Open the notebook in Google Colab.
2. Upload `synthetic_text_data.csv`.
3. Install the required libraries if necessary.
4. Run all notebook cells in order.
5. Test the model with new text.

## Project Status

Basic text classification implemented using Multinomial Naive Bayes.

## Future Improvements

- Compare CountVectorizer with TF-IDF.
- Compare Naive Bayes with Logistic Regression.
- Evaluate performance on a larger, real-world dataset.
- Improve classification performance using hyperparameter tuning.
