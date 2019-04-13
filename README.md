# DATA SCIENCE

This repository stores [Jupyter Notebooks] to demonstrate skills in [Data Science], [Artificial Intelligence], classification and regression problems with [Python], [Keras], [scikit-learn], [Matplotlib], [NumPy], [Pandas], [TPOT], [XGBoost], [Folium], [Seaborn] among others.

## DEPENDENCIES

The code has been tested using:

* [Python] (3.6.8): an interpreted high-level programming language for general-purpose programming.
* [Keras] (2.2.4): a high-level neural networks [API], written in [Python] and capable of running on top of [TensorFlow], CNTK, or Theano.
* [Tensorflow] (1.13.1): an open source [Deep Learning] library for high performance numerical computation using data flow graphs.
* [Matplotlib] (3.0.3): a plotting library for [Python] and its numerical mathematics extension [NumPy].
* [NumPy] (1.16.2): a library for [Python], adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
* [Pandas] (0.24.2):  an open source library providing high-performance, easy-to-use data structures and data analysis tools for [Python].
* [scikit-learn] (0.20.3): a [machine learning] library for [Python]. It features various classification, regression and clustering algorithms including support vector machines, [random forest], [gradient boosting], k-means and DBSCAN.
* [scikit-image] (0.15.0): a collection of algorithms for image processing with [Python].
* [TPOT] (0.10.0): a [Python] Automated [Machine Learning] tool that optimizes [machine learning] pipelines using genetic programming.
* [XGBoost] (0.82): an optimized distributed [gradient boosting] library designed to be highly efficient, flexible and portable.
* [Folium] (0.8.3): an open source library to visualize data that has been manipulated in [Python] on an interactive [Leaflet.js] map.
* [ipyleaflet] (0.10.1): a [Jupyter] / [Leaflet.js] bridge enabling interactive maps in the [Jupyter notebook].
* [Seaborn] (0.9.0): a [Python] visualization library based on [Matplotlib]. It provides a high-level interface for drawing attractive statistical graphics.
* [imbalanced-learn] (0.4.3): a [Python] package offering a number of re-sampling techniques commonly used in datasets showing strong between-class imbalance. It is compatible with [scikit-learn] and it allows [SMOTE (Synthetic Minority Over-sampling Technique)].
* [joblib] (0.13.2): a set of tools to provide lightweight pipelining in [Python].
* [findspark] (1.3.0): a package to make [Spark] Context available in [Jupyter Notebook].
* [Conda] (4.6.11): a virtual environment included in [Python] Data Science Platform [Anaconda].

Virtual environment (<env_name>=**datascience36**) can be generated with **datascience36.yaml**, **requirements.txt** files found in main folder.

Command to configure virtual environment with [Conda]:

```bash
~/datascience$ conda env create -f datascience36.yaml
~/datascience$ conda activate datascience36
(datascience36)~/datascience$
```

Commands to configure virtual environment with [virtualenv]:

```bash
~/datascience$ virtualenv datascience36
~/datascience$ source datascience36/bin/activate
(datascience36)~/datascience$ pip install -r requirements.txt
```

It could be required to be able to use libraries dependent on [Python] widgets to execute the command:

```bash
~$ jupyter nbextension enable --py --sys-prefix widgetsnbextension
```

It might be also necessary to install locally [Graphviz] for rendering graph images with the command:

```bash
~/datascience$ sudo apt-get install graphviz
```

Graph image example of a decision tree is shown below.

![Graph image example of a decision tree](images/tree_top3.png)

[Data Science]: https://en.wikipedia.org/wiki/Data_science
[Artificial Intelligence]: https://en.wikipedia.org/wiki/Artificial_intelligence
[Python]: https://www.python.org/
[Machine Learning]: https://en.wikipedia.org/wiki/Machine_learning
[Deep Learning]: https://en.wikipedia.org/wiki/Deep_learning
[Random Forest]: https://en.wikipedia.org/wiki/Random_forest
[Gradient Boosting]: https://en.wikipedia.org/wiki/Gradient_boosting
[API]: https://en.wikipedia.org/wiki/Application_programming_interface
[Docker]: https://www.docker.com/
[docker-compose]: https://github.com/docker/compose
[Keras]: https://keras.io/
[Tensorflow]: https://www.tensorflow.org/
[Matplotlib]: https://matplotlib.org/
[NumPy]: http://www.numpy.org/
[Pandas]: https://pandas.pydata.org/
[scikit-learn]: http://scikit-learn.org/stable/
[scikit-image]: https://scikit-image.org/
[TPOT]: https://github.com/EpistasisLab/tpot
[XGBoost]: https://github.com/dmlc/xgboost
[Folium]: https://github.com/python-visualization/folium
[Leaflet.js]: https://leafletjs.com/
[ipyleaflet]: https://github.com/jupyter-widgets/ipyleaflet
[Seaborn]: http://seaborn.pydata.org/
[imbalanced-learn]: https://github.com/scikit-learn-contrib/imbalanced-learn
[SMOTE (Synthetic Minority Over-sampling Technique)]: https://jair.org/index.php/jair/article/view/10302
[joblib]: https://pypi.org/project/joblib/
[Jupyter]: http://jupyter.org/
[Jupyter Notebook]: http://jupyter.org/
[Jupyter Notebooks]: http://jupyter.org/
[findspark]: https://github.com/minrk/findspark
[Spark]: https://spark.apache.org/
[Conda]: https://conda.io/docs/index.html
[Anaconda]: https://www.anaconda.com/
[virtualenv]: https://virtualenv.pypa.io/en/stable/
[Graphviz]: https://www.graphviz.org/
