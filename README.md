# tiny-sklearn

## About
- Tiny implementation of important algorithms in scikit-learn
(e.g., pure python, no input validation, no speed/memory optimization, do not support sparse matrix and multioutput).
- Useful when understanding ML algorithms and scikit-learn.
- Multiple implementations of each algorithm.
- Roughly follow the structure of scikit-learn.
- Roughly follow the API standard of scikit-learn.
- Results are compared with scikit-learn.
- Under construction.

## Table of Contents
- cluster (sklearn.cluster)
  * [DBSCAN](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/cluster/DBSCAN.ipynb)
- decomposition (sklearn.decomposition)
  * [PCA](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/decomposition/PCA.ipynb)
- ensemble (sklearn.ensemble)
  * [VotingClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/ensemble/VotingClassifier.ipynb)
  * [VotingRegressor](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/ensemble/VotingRegressor.ipynb)
- **kernel\_ridge** (sklearn.kernel\_ridge)
  * [KernelRidge](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/kernel_ridge/KernelRidge.ipynb)
- linear\_model (sklearn.linear\_model)
  * [LinearRegression](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/linear_model/LinearRegression.ipynb)
  * [LogisticRegression](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/linear_model/LogisticRegression.ipynb)
  * [Ridge](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/linear_model/Ridge.ipynb)
  * [RidgeClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/linear_model/RidgeClassifier.ipynb)
- neighbors (sklearn.neighbors)
  * [KNeighborsClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/neighbors/KNeighborsClassifier.ipynb)
  * [KNeighborsRegressor](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/neighbors/KNeighborsRegressor.ipynb)
  * [NearestNeighbors](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/neighbors/NearestNeighbors.ipynb)
  * [RadiusNeighborsClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/neighbors/RadiusNeighborsClassifier.ipynb)
  * [RadiusNeighborsRegressor](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/neighbors/RadiusNeighborsRegressor.ipynb)
- **multiclass** (sklearn.multiclass)
  * [OneVsOneClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/multiclass/OneVsOneClassifier.ipynb)
  * [OneVsRestClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/multiclass/OneVsRestClassifier.ipynb)
  * [OutputCodeClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/multiclass/OutputCodeClassifier.ipynb)
- **naive\_bayes** (sklearn.naive\_bayes)
  * [BernoulliNB](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/naive_bayes/BernoulliNB.ipynb)
  * [ComplementNB](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/naive_bayes/ComplementNB.ipynb)
  * [GaussianNB](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/naive_bayes/GaussianNB.ipynb)
  * [MultinomialNB](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/naive_bayes/MultinomialNB.ipynb)
- preprocessing (sklearn.preprocessing)
  * [KernelCenterer](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/KernelCenterer.ipynb)
  * [LabelBinarizer](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/LabelBinarizer.ipynb)
  * [LabelEncoder](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/LabelEncoder.ipynb)
  * [MaxAbsScaler](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/MaxAbsScaler.ipynb)
  * [MinMaxScaler](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/MinMaxScaler.ipynb)
  * [Normalizer](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/Normalizer.ipynb)
  * [RobustScaler](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/RobustScaler.ipynb)
  * [StandardScaler](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/StandardScaler.ipynb)
