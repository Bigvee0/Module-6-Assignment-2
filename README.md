# Fashion MNIST CNN Assignment

This project implements a 6-layer CNN for Fashion MNIST classification.

## Files
- `fashion_mnist_cnn.py`: Python script.
- `fashion_mnist_cnn.R`: R script.
- `prediction_1.png`, `prediction_2.png`: Visualizations.
- `README.md`: This file.

## Setup
1. Conda environment with Python 3.11 and TensorFlow 2.16.1:
   ```bash
   conda create -n tf_env python=3.11
   conda activate tf_env
   pip install tensorflow==2.16.1 numpy matplotlib
   ```
2. R 4.5.1 with reticulate:
   ```R
   install.packages('reticulate')
   ```
3. Dataset: `tf.keras.datasets.fashion_mnist` (https://keras.io/api/datasets/fashion_mnist/).

## Usage
```bash
python fashion_mnist_cnn.py
Rscript fashion_mnist_cnn.R
```

## Output
- Accuracy: ~90.5%.
- Visualizations for two test images.
