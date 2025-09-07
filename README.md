# Supervised-Learning-Final-Project
## Project Overview 
This project focuses on building a robust classification model to solve a common e-commerce problem: automatically assigning new products to the correct category. The solution is a machine learning pipeline that takes raw product titles, processes the text data, and predicts one of 10 distinct product categories.

### Key Components
* Problem: To build an accurate classifier that predicts a product's category from its title.

* Dataset: Product Classification and Clustering Dataset from the UCI Machine Learning Repository.

* Methodology:

  * 1.Data Cleaning & EDA: Initial inspection and cleaning of the dataset, with a focus on preparing the unstructured text data.

  * 2.Text Preprocessing: Used a pipeline for lowercasing and removing special characters.

  * 3.Feature Engineering: Employed TF-IDF Vectorization to convert cleaned text into a numerical feature matrix.

  * 4.Model Training: Trained a Logistic Regression model on the vectorized data.

* Results: The final model achieved an accuracy of 95.6% on the test set, demonstrating its strong performance and reliability.

### Repository Contents

* Product Category Classification.ipynb: The main Jupyter notebook containing the full project analysis, from problem description to conclusion.

* pricerunner_aggregate.csv: The raw data file

### How to run the Project

To replicate the project, you can download the Jupyter notebook and run it in a Python environment with the required libraries installed.

* Required Libraries:
  * pandas

  * scikit-learn

  * matplotlib

  * seaborn

  * nltk

You can install all dependencies using pip:

pip install pandas scikit-learn matplotlib seaborn nltk

### Author: 
Giacomo Piseddu
giacomo.piseddu@colorado.edu
