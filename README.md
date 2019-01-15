# Test-Accuracy-of-Supervised-Classifiers
Three supervised machine learning algorithms (SVM, Decision Tree and Random Forests) used on three different datasets.

There are 4 main components to this experiment. The first component are the 3 datasets. The second component are the 3 classifiers. The third component are the 3 partitions. The original data is split into training and testing sets. There are three ways in how the data is split, these types of partitions are, (80% train, 20% test), (50% train, 50% test), and (20% train, 80% test). The fourth component is the 3 trials, in where each trial is done on a randomized shuffle of the original data. 

When described in a sequential structure it is as follows; 3 datasets, each undergoing 3 classifiers, each classifier consists of 3 partitions and each partition consists of 3 runs. In which each of these runs is essentially a shuffle of the original dataset.

## Getting Started

### Prerequisites

Install the latest version of python and download Anaconda Distribution for Jupyter Notebook.

## Running the tests

Compile and run each of the three ipynb files on jupyter notebook.

### Example Run

Example run demonstration for the three datasets are shown in the following files:

* [Code_pdf_EEG.pdf](Code_pdf_EEG.pdf)
* [Code_pdf_Seeds.pdf](Code_pdf_Seeds.pdf)
* [Code_pdf_Wine.pdf](Code_pdf_Wine.pdf)

![eegeyedataresults](https://user-images.githubusercontent.com/32502126/51213981-5e401400-18d1-11e9-8d6e-6192b65a99d0.png)

## Authors

* **Rodrigo Efraim** - *Initial work* - [RodEfraim](https://github.com/RodEfraim)

## Acknowledgments

Caruana R. Niculescu-Mizil A. (2006, June). An empirical comparison of supervised learning algorithms. The Proceedings of the 23rd International Conference on Machine Learning (pp. 161-168). ACM.

[sklearn svm SVC](
https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html#sklearn.svm.SVC)

[sklearn Decision Tree Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)

[sklearn Random Forest Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)

[Hyperparameter Tuning the Random Forest in Python](https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74)

[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets.html)
