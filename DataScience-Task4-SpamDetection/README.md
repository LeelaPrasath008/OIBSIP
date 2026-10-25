# Email Spam Detection with Machine Learning

## Project Overview

This project uses Natural Language Processing (NLP) and machine learning to classify text messages as spam or ham (legitimate messages). The project demonstrates how text preprocessing, TF-IDF feature extraction, and supervised learning can be combined to build a spam classification system.

## Objectives

- Explore and clean a labelled text-message dataset.
- Examine the distribution of spam and ham messages.
- Preprocess text for machine learning.
- Convert messages into numerical features using TF-IDF.
- Train and compare Multinomial Naive Bayes and Logistic Regression.
- Evaluate models using accuracy, precision, recall, F1-score, and confusion matrices.
- Visualize frequently occurring words using WordClouds.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Regular expressions (`re`)
- WordCloud
- Jupyter Notebook

## Dataset

The project uses the SMS Spam Collection dataset from the UCI Machine Learning Repository.

Dataset source: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

The dataset contains labelled messages categorized as `spam` or `ham`. Although the task is titled Email Spam Detection, this project uses the SMS dataset recommended in the task instructions.

## Project Structure

```text
DataScience-Task4-SpamDetection/
├── Spam_Detection.ipynb
├── SMSSpamCollection
├── README.md
├── screenshots/
└── outputs/
```

## Project Workflow

1. Load and explore the dataset.
2. Examine class distribution and duplicate records.
3. Clean and preprocess message text.
4. Split the data into training and testing sets.
5. Extract TF-IDF features within machine learning pipelines.
6. Train Multinomial Naive Bayes and Logistic Regression classifiers.
7. Evaluate and compare model performance.
8. Visualize confusion matrices and word clouds.
9. Summarize findings and conclusions.

## How to Run the Project

1. Install Python and Jupyter Notebook.
2. Open a terminal in the project directory.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn wordcloud jupyter
   ```

4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Spam_Detection.ipynb` and run the cells in order.

## Evaluation

The notebook evaluates both classifiers using accuracy, spam precision, spam recall, and spam F1-score. Confusion matrices are used to examine correctly classified messages and classification errors.

The measured results are recorded in the notebook. Performance on other datasets or real-world messages may differ.

## Learning Outcomes

This project provides practical experience with text preprocessing, TF-IDF feature extraction, supervised machine learning, classification metrics, and data visualization.

## Author

Leelaprasath V.
