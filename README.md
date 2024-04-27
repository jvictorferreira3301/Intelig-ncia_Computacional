# Classifiers Project - 2024

This repository contains the code, reports, and associated presentations for the Classifiers Project of the Computational Intelligence course taught in the seventh semester of the Computer Engineering and Telecommunications Faculty at the Federal University of Pará.

## Project Structure

The project is organized into two distinct parts:

### Part I - MNIST

In this part, teams will work with the `MNIST` dataset of ZIP code digits. In addition to the original digits, versions with Gaussian noise were generated for training, testing, and validation. Each team generated its own sets, with the test set being disjoint from the others.

### Part II - Custom Dataset

In this part, teams chose a dataset for classification with a minimum of 200 examples and repeated the procedure from Part I, without considering the insertion of noise.

We chose the dataset `credit_data.csv` (https://www.kaggle.com/datasets/laotse/credit-risk-dataset) which contains columns that simulate data from credit agencies. The attributes are the `income`, `age`, `loan` columns and the class is the `default` column, classifying those who pay loans with `1` and those who don't pay with `0`.

## Team

- [João Victor Ferreira](https://github.com/jvictorferreira3301)
- [Valdinei Conceição](https://github.com/Manky0)
- [Ryan Oliveira](https://github.com/ASTRAson)
  
## Classifiers Used

- [Decision Trees](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)
- [Naive Bayes](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.GaussianNB.html)
- [SVM](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)
