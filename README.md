# This is a CNN model trained to identify hair types using the given dataset.
## Prerequisites

1. Make sure to have Python installed. For Conda, there is no available Tensorflow versions available for Python 3.12. To downgrade, use this commands
```
conda install python=3.x
```
where x is the version you want to downgrade to
Additionally, the conda package ipykernel is also needed to run Jupyter notebooks
```
conda install ipykernel
```

2. Install the following packages using PiP
```
pip install pandas
pip install numpy
pip install matplotlib
pip install tensorflow
```

3. Make sure to unzip the hair_types folder; by default, it is included in the .gitignore file since it is too large.

4. These are additional packages needed for the plot_model function to work
```
pip install pydot
```
For graphviz, here is the website for guides to install for your specific Operating System
```
https://graphviz.gitlab.io/download/
```
