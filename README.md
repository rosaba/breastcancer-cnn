# BreastCancer
ConvNet for classification of breastcancer (IDC)

# Installation

1. Install Jupyter Notebook: https://jupyter.org/install
2. Download dataset from kaggle: https://www.kaggle.com/paultimothymooney/breast-histopathology-images/data
3. Download this git repository
4. set up project (virtual environment, dependencies -> see next step)

## Prepare virtual environment and set up dependencies (using pip or conda)

For pip (https://www.tensorflow.org/install/pip):
1. Make sure you have Python3, virtualenv and pip3 installed
   -> versions we used:
      Python		3.6.9
      pip3		19.3.1
      virtualenv	16.7.8
2. create virtual environment
   -> virtualenv --system-site-packages -p python3 ./VENVNAME
3. activate the venv:
   -> source ./VENVNAME/bin/activate
4. Now you are inside your virtual environment. Install:
   -> pip install --upgrade pip
   -> pip list  # show packages installed within the virtual environment
5. Install Tensorflow
   -> pip install --upgrade tensorflow
      (for now we installed: Latest stable release (2.x) for CPU-only (recommended for beginners).
      (maybe for later we could use: tensorflow-gpu ???)
   -> verify installation:
      python -c "import tensorflow as tf;print(tf.reduce_sum(tf.random.normal([1000, 1000])))"
6. leave virtual environment (when your done):
   -> deactivate


## Tensorflow tutorials:
https://www.tensorflow.org/tutorials 
