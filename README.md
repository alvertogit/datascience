# DATA SCIENCE

This repository stores Jupyter notebooks to demonstrate skills in [Data Science], [Artificial Intelligence], classification and regression problems with [Python], [Keras], [Matplotlib], [NumPy], [Pandas], [Folium], [Seaborn].

## DEPENDENCIES
The code has been tested using:

* [Python] (3.6.6): an interpreted high-level programming language for general-purpose programming.
* [Keras] (2.2.0): a high-level neural networks API, written in [Python] and capable of running on top of [TensorFlow], CNTK, or Theano.
* [Tensorflow] (1.8.0): an open source software library for high performance numerical computation using data flow graphs.
* [Matplotlib] (2.2.2): a plotting library for [Python] and its numerical mathematics extension [NumPy].
* [NumPy] (1.14.5): a library for [Python], adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
* [Pandas] (0.23.1):  an open source library providing high-performance, easy-to-use data structures and data analysis tools for [Python].
* [scikit-learn] (0.19.1): a machine learning library for [Python]. It features various classification, regression and clustering algorithms including support vector machines, random forests, gradient boosting, k-means and DBSCAN.
* [TPOT] (0.9.3): a [Python] Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming.
* [Folium] (0.5.0): an open source library to visualize data that’s been manipulated in Python on an interactive [Leaflet.js] map.
* [Seaborn] (0.8.1): a [Python] visualization library based on [Matplotlib]. It provides a high-level interface for drawing attractive statistical graphics.
* [Conda] (4.5.4): a virtual environment included in [Python] Data Science Platform [Anaconda].

Virtual environment (<env_name>=datascience36) can be generated with **datascience36.yaml**, **requirements.txt** files found in main folder.

Command to configure virtual environment with [Conda]:

```bash
~/datascience$ conda env create -f datascience36.yaml
~/datascience$ source activate datascience36
(datascience36)~/datascience$
```

Commands to configure virtual environment with [virtualenv]:

```bash
~/datascience$ virtualenv datascience36
~/datascience$ source datascience36/bin/activate
(datascience36)~/datascience$ pip install -r requirements.txt
```

It might be also necessary to install locally [Graphviz] for rendering graph images.
```bash
$ sudo apt-get install graphviz
```

[Data Science]: https://en.wikipedia.org/wiki/Data_science
[Artificial Intelligence]: https://en.wikipedia.org/wiki/Artificial_intelligence
[Python]: https://www.python.org/
[Keras]: https://keras.io/
[Tensorflow]: https://www.tensorflow.org/
[Matplotlib]: https://matplotlib.org/
[NumPy]: http://www.numpy.org/
[Pandas]: https://pandas.pydata.org/
[scikit-learn]: http://scikit-learn.org/stable/
[TPOT]: https://github.com/EpistasisLab/tpot
[Folium]: https://github.com/python-visualization/folium
[Leaflet.js]: https://leafletjs.com/
[Seaborn]: http://seaborn.pydata.org/
[Conda]: https://conda.io/docs/index.html
[Anaconda]: https://www.anaconda.com/
[virtualenv]: https://virtualenv.pypa.io/en/stable/
[Graphviz]: https://www.graphviz.org/