# 1. This is a CNN model trained to identify hair types using the given dataset

- [1. This is a CNN model trained to identify hair types using the given dataset](#1-this-is-a-cnn-model-trained-to-identify-hair-types-using-the-given-dataset)
  - [1.1. Prerequisites](#11-prerequisites)

## 1.1. Prerequisites

1. Make sure to have Python installed. For Conda, there is no available Tensorflow versions available for Python 3.12. To downgrade, use this commands

```Python
conda install python=3.x
```

where x is the version you want to downgrade to

Additionally, the conda package ipykernel is also needed to run Jupyter notebooks

```Python
conda install ipykernel
```

2. Install the following packages using PiP

```Python
pip install pandas
pip install numpy
pip install matplotlib
pip install tensorflow
```

3. Make sure to unzip the hair_types folder; by default, it is included in the .gitignore file since it is too large.

4. These are additional packages needed for the plot_model function to work

```Python
pip install pydot
```

For graphviz, here is the website for guides to install for your specific Operating System

```Python
https://graphviz.gitlab.io/download/
```

5. For MacOS, refer to the guide of installing Tensorflow below to avoid kernel issues and version miscompatibilities

```Python
https://developer.apple.com/metal/tensorflow-plugin/
```
