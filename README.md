# 2D-Visualization-of-MNIST-Dataset-
Visualizing a 784 dimensional dataset(MNIST) in 2d using PCA

### Tech Stack

  1) Seaborn
  2) Matplotlib
  3) Scipy
  4) Scikit-learn
  5) Numpy

### My approach to the problem
  1) Standardize The Data 
  2) Compute the co-variance Matrix of it
  3) Compute the Eigen Values and Their Corresponding Eigen Vectors
  4) Take the top two maximum eigen values and their corresponding eigen vectors
  5) Project the standardized data on the plane formed by two principal eigen vectors by vector-vector multiplication.
  6) Append the labels to the 2D projected data
  6) Create a new dataframe for plotting our labeled points
  7) Plot the data on a 2D plane with x being the 1st principal and y being the 2nd principal and hue=label
  

## How to run

1) Download the MNIST data from https://www.kaggle.com/c/digit-recognizer
2) Copy the train.csv file
3) Paste it in the same folder where the jupyter notebook exists
4) Open the jupyter notebook and run code
