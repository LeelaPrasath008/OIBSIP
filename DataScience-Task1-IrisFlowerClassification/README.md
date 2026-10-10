# Iris Flower Classification 🌸

## Oasis Infobyte Data Science Internship — Task 1

### Project Overview

This project uses machine learning to classify Iris flowers into three species: Setosa, Versicolor, and Virginica, based on their sepal and petal measurements.

### Objectives

* Explore the Iris dataset.
* Perform exploratory data analysis (EDA).
* Visualize flower measurements using pairplots and boxplots.
* Train and compare two machine learning models.
* Evaluate the models using accuracy, confusion matrices, precision, recall, and F1-score.

### Technologies Used

* Python
* Jupyter Notebook
* pandas
* scikit-learn
* Matplotlib
* Seaborn

### Dataset

The dataset is loaded using `sklearn.datasets.load_iris()`.

* **Total samples:** 150
* **Features:** 4 numerical measurements
* **Target classes:** Setosa, Versicolor, Virginica
* **Missing values:** None

### Workflow

1. Load and inspect the dataset.
2. Perform exploratory data analysis.
3. Create pairplots and boxplots.
4. Split the dataset into 80% training data and 20% testing data.
5. Train Logistic Regression and K-Nearest Neighbours (KNN).
6. Evaluate and compare model performance.

### Results

| Model                      | Test Accuracy |
| -------------------------- | ------------: |
| Logistic Regression        |        93.33% |
| K-Nearest Neighbours (KNN) |        93.33% |

Both models correctly classified 28 out of 30 test samples. Logistic Regression was selected as the preferred model for this experiment based on its per-class performance.

### How to Run

1. Install Python or Anaconda.

2. Install the required libraries:

   `pip install pandas scikit-learn matplotlib seaborn notebook`

3. Open a terminal in the project folder and run:

   `jupyter notebook`

4. Open `Iris_Flower_Classification.ipynb`.

5. Run the notebook cells from top to bottom.

### Limitations

The evaluation uses a single train-test split with 30 test samples. Results may vary with different data splits, so further validation is recommended.

### Conclusion

This project demonstrates a machine learning classification workflow involving data exploration, visualization, model training, and evaluation using the Iris dataset.
