# DATA SCIENCE

This repository stores Jupyter notebooks to demonstrate skills mainly with Python, Keras, matplotlib, numpy, seaborn.

## DEPENDENCIES
The code has been tested using:

* Python (3.6.5)
* Keras (2.1.5)
* Tensorflow (1.6.0)
* Matplotlib (2.2.0)
* Numpy (1.14.5)
* Seaborn (0.8.1)
* Conda (4.4.11) virtual environment (<env_name>=datascience36)

Virtual environment can be generated with **datascience36.yaml**, **requirements.txt** files found in main folder.

Command to configure virtual environment with **conda**:

```bash
~/datascience$ conda env create -f datascience36.yaml
```

Commands to configure virtual environment with **virtualenv**:

```bash
~/datascience$ virtualenv datascience36
~/datascience$ source datascience36/bin/activate
(datascience36)~/datascience$ pip install -r requirements.txt
```