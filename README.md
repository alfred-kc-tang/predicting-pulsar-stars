# [Predicting Pulsar Stars using scikit-learn](https://alfred-kctang.github.io/predicting-pulsar-stars/)

This project utilizes the scikit-learn library to build various machine learning models, namely (1) Linear Regression, (2) Random Forest, (3) Support Vector Machine, as well as a commonly used technique when building models - Principal Component Analysis, in order to predict a given star is a pulsar or not. Of course, Hyperparameters tuning has to be performed, but this time by using the [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html) function provided by scikit-learn.

## Table of Contents

* [Data Source](#data-source)
* [Keywords](#keywords)
* [Coding Style](#coding-style)
* [License](#license)

## Data Source

The data set is from a [Kaggle competition](https://www.kaggle.com/colearninglounge/predicting-pulsar-starintermediate). The dataset has been cleaned that data with missing attributes were removed. Each line in the csv file describes an instance using 9 columns: the first 8 columns represent the attributes of the pulsar candidate, namely mean of the integrated profile, standard deviation of the integrated profile, excess kurtosis of the integrated profile, skewness of the integrated profile, mean of the DM-SNR curve, standard deviation of the DM-SNR curve, excess kurtosis of the DM-SNR curve, skewness of the DM-SNR curve; whereas the last column is the response variable that tells us if the observation is a pulsar or not (1 means it is a pulsar, 0 means it is not).

## Keywords

Linear Regression; Principal Component Analysis (PCA); Random Forest; scikit-learn; Singular Value Decomposition (SVD); Support Vector Machine (SVM).

## Coding Style

This project adopts the recommended practice of [PEP 8](https://www.python.org/dev/peps/pep-0008/) as well as [PEP 257](https://www.python.org/dev/peps/pep-0257/), and also by reference to [Google's Python Style Guide](https://google.github.io/styleguide/pyguide.html).

## License

This repository is covered under the [MIT License](https://github.com/alfred-kctang/random-forest-pulsar-stars/blob/master/LICENSE).
