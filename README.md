# VAE Model

This repository contains the implementation of a Variational Autoencoder (VAE) using TensorFlow and Keras. The VAE is trained on a dataset of images and can generate new images with similar characteristics. Additionally, the repository includes scripts for evaluating the trained model using various metrics such as FID (Fréchet Inception Distance), KID (Kernel Inception Distance), PSNR (Peak Signal-to-Noise Ratio), and Inception Score.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- TensorFlow
- Keras
- NumPy
- Matplotlib
- PIL (Pillow)
- Scikit-learn
- Pandas

### Dataset

The VAE model is trained on a dataset located in the `data/training` directory. The dataset should be organized into classes, with each class in a separate subdirectory.

The testing dataset is located in the `data/testing` directory.

### Results
The results, including FID, KID, PSNR, and Inception Scores, are saved in CSV files for analysis. The files are named fid_kid_scores.csv, output_psnr.csv, and inception_scores.csv.

Additionally, loss plots during training are saved in the Models/None_Models directory.
