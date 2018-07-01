# DATA SCIENCE

This repository stores Jupyter notebooks to demonstrate skills in [Data Science], [Artificial Intelligence], classification and regression problems with [Python], [Keras], [Matplotlib], [NumPy], [Pandas], [Seaborn].

## DEPENDENCIES
The code has been tested using:

* [Python] (3.6.5)
* [Keras] (2.1.5)
* [Tensorflow] (1.6.0)
* [Matplotlib] (2.2.0)
* [NumPy] (1.14.5)
* [Pandas] (0.23.1)
* [Seaborn] (0.8.1)
* [Conda] (4.5.4) virtual environment (<env_name>=datascience36) included in [Python] Data Science Platform [Anaconda]

Virtual environment can be generated with **datascience36.yaml**, **requirements.txt** files found in main folder.

Command to configure virtual environment with [conda]:

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

[Data Science]: https://en.wikipedia.org/wiki/Data_science
[Artificial Intelligence]: https://en.wikipedia.org/wiki/Artificial_intelligence
[Python]: https://www.python.org/
[Keras]: https://keras.io/
[Tensorflow]: https://www.tensorflow.org/
[Matplotlib]: https://matplotlib.org/
[NumPy]: http://www.numpy.org/
[Pandas]: https://pandas.pydata.org/
[Seaborn]: http://seaborn.pydata.org/
[Conda]: https://conda.io/docs/index.html
[Anaconda]: https://www.anaconda.com/
[virtualenv]: https://virtualenv.pypa.io/en/stable/