# tiny-sklearn

## About
- Tiny implementation of important algorithms in scikit-learn
(e.g., pure python, no input validation, no speed/memory optimization, do not support sparse matrix and multioutput).
- Useful when understanding ML algorithms and scikit-learn.
- Multiple implementations of each algorithm.
- Roughly follow the structure of scikit-learn.
- Roughly follow the API standard of scikit-learn.
- Results are compared with scikit-learn.

## Table of Contents
- calibration (sklearn.calibration)
- cluster (sklearn.cluster)
  * [DBSCAN](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/cluster/DBSCAN.ipynb)
- **covariance** (sklearn.covariance)
  * [EmpiricalCovariance](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/covariance/EmpiricalCovariance.ipynb)
- decomposition (sklearn.decomposition)
  * [KernelPCA](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/decomposition/KernelPCA.ipynb)
  * [PCA](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/decomposition/PCA.ipynb)
- **discriminant_analysis** (sklearn.discriminant_analysis)
  * [LinearDiscriminantAnalysis](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/discriminant_analysis/LinearDiscriminantAnalysis.ipynb)
- dummy (sklearn.dummy)
- ensemble (sklearn.ensemble)
  * [BaggingClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/ensemble/BaggingClassifier.ipynb)
  * [BaggingRegressor](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/ensemble/BaggingRegressor.ipynb)
  * [VotingClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/ensemble/VotingClassifier.ipynb)
  * [VotingRegressor](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/ensemble/VotingRegressor.ipynb)
- **feature_extraction** (sklearn.feature_extraction)
  * [CountVectorizer](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/feature_extraction/CountVectorizer.ipynb)
  * [TfidfTransformer](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/feature_extraction/TfidfTransformer.ipynb)
  * [TfidfVectorizer](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/feature_extraction/TfidfVectorizer.ipynb)
- feature_selection (sklearn.feature_selection)
- **impute** (sklearn.inpute)
  * [MissingIndicator](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/impute/MissingIndicator.ipynb)
  * [SimpleImputer](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/impute/SimpleImputer.ipynb)
- inspection (sklearn.inspection)
- **kernel_ridge** (sklearn.kernel_ridge)
  * [KernelRidge](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/kernel_ridge/KernelRidge.ipynb)
- linear_model (sklearn.linear_model)
  * [LinearRegression](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/linear_model/LinearRegression.ipynb)
  * [LogisticRegression](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/linear_model/LogisticRegression.ipynb)
  * [Ridge](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/linear_model/Ridge.ipynb)
  * [RidgeClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/linear_model/RidgeClassifier.ipynb)
- metrics (sklearn.metrics) - classification metrics
  * [accuracy_score](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/metrics/accuracy_score.ipynb)
  * [confusion_matrix](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/metrics/confusion_matrix.ipynb)
  * [f1_score](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/metrics/f1_score.ipynb)
  * [fbeta_score](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/metrics/fbeta_score.ipynb)
  * [multilabel_confusion_matrix](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/metrics/multilabel_confusion_matrix.ipynb)
  * [precision_score](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/metrics/precision_score.ipynb)
  * [recall_score](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/metrics/recall_score.ipynb)
- metrics (sklearn.metrics) - regression metrics
  * [r2_score](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/metrics/r2_score.ipynb)
- metrics (sklearn.metrics) - clustring metrics
- metrics (sklearn.metrics) - pairwise metrics
  * [linear_kernel](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/metrics/linear_kernel.ipynb)
  * [rbf_kernel](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/metrics/rbf_kernel.ipynb)
- **mixture** (sklearn.mixture)
  * [GaussianMixture](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/mixture/GaussianMixture.ipynb)
- neighbors (sklearn.neighbors)
  * [KNeighborsClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/neighbors/KNeighborsClassifier.ipynb)
  * [KNeighborsRegressor](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/neighbors/KNeighborsRegressor.ipynb)
  * [NearestNeighbors](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/neighbors/NearestNeighbors.ipynb)
  * [RadiusNeighborsClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/neighbors/RadiusNeighborsClassifier.ipynb)
  * [RadiusNeighborsRegressor](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/neighbors/RadiusNeighborsRegressor.ipynb)
- model_selection (sklearn.model_selection) - splitter classes
- model_selection (sklearn.model_selection) - hyper-parameter optimizers
- model_selection (sklearn.model_selection) - model validation
- **multiclass** (sklearn.multiclass)
  * [OneVsOneClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/multiclass/OneVsOneClassifier.ipynb)
  * [OneVsRestClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/multiclass/OneVsRestClassifier.ipynb)
  * [OutputCodeClassifier](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/multiclass/OutputCodeClassifier.ipynb)
- **naive_bayes** (sklearn.naive_bayes)
  * [BernoulliNB](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/naive_bayes/BernoulliNB.ipynb)
  * [ComplementNB](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/naive_bayes/ComplementNB.ipynb)
  * [GaussianNB](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/naive_bayes/GaussianNB.ipynb)
  * [MultinomialNB](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/naive_bayes/MultinomialNB.ipynb)
- neural_network (sklearn.neural_network)
- preprocessing (sklearn.preprocessing)
  * [KernelCenterer](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/KernelCenterer.ipynb)
  * [LabelBinarizer](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/LabelBinarizer.ipynb)
  * [LabelEncoder](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/LabelEncoder.ipynb)
  * [MaxAbsScaler](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/MaxAbsScaler.ipynb)
  * [MinMaxScaler](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/MinMaxScaler.ipynb)
  * [Normalizer](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/Normalizer.ipynb)
  * [RobustScaler](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/RobustScaler.ipynb)
  * [StandardScaler](https://nbviewer.jupyter.org/github/qinhanmin2014/tiny-sklearn/blob/master/preprocessing/StandardScaler.ipynb)
- svm (sklearn.svm)
- tree (sklearn.tree)
