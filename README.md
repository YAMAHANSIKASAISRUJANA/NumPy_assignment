# NumPy Assignment

This repository contains basic NumPy programs created as part of Python and Machine Learning practice.

The programs are included in a single Jupyter Notebook, `numpy_assignment.ipynb`. The notebook covers NumPy array operations, mathematical operations, feature matrices, image arrays, broadcasting, MSE, normalization, and standardization.

## Topics Covered

* Creating NumPy arrays
* `np.arange()`
* `np.zeros()`
* Array dimensions (`ndim`)
* Array shape (`shape`)
* Array size (`size`)
* Array data type (`dtype`)
* Indexing
* Slicing
* Reshaping
* Transpose
* Arithmetic operations
* Feature matrices
* Mean using `axis=0`
* Filtering rows
* Standardization
* Random matrices
* Matrix multiplication
* Broadcasting
* Mean Squared Error (MSE)
* Grayscale images
* RGB image batches
* Handling `NaN` values
* Element-wise multiplication
* Matrix multiplication
* Normalization
* Standardization

## Programs Included

### 1. NumPy Array from 10 to 100

Creates an array containing numbers from 10 to 100 with a step of 10.

### 2. 3 × 4 Zero Array

Creates a 3 × 4 array containing zeros.

### 3. Array Attributes

Prints the dimensions, shape, size, and data type of an array.

### 4. Last Element

Extracts the last element from a 1D array using indexing.

### 5. First Two Columns

Selects the first two columns from a 2D array using slicing.

### 6. Reshaping

Reshapes 12 numbers into a 3 × 4 matrix.

### 7. Transpose

Transposes a 2 × 3 matrix.

### 8. Multiplication

Multiplies every element of an array by 5.

### 9. Feature Matrix

Creates a feature matrix containing 5 samples and 3 features and prints its shape.

### 10. Feature Mean

Calculates the mean of each feature using `axis=0`.

### 11. Filtering Rows

Selects rows where the first feature is greater than 50.

### 12. Standardization

Standardizes each feature column using mean and standard deviation.

### 13. Random Matrix

Creates a random matrix of shape `(10, 4)` using a fixed seed.

### 14. Matrix and Weight Multiplication

Calculates `X @ weights` using a feature matrix and weight vector.

### 15. Broadcasting

Adds a bias vector to a matrix using NumPy broadcasting.

### 16. Mean Squared Error

Calculates MSE between actual and predicted values.

### 17. Grayscale Image

Creates a 28 × 28 grayscale image array and prints its shape.

### 18. RGB Image Batch

Creates a batch of 64 RGB images of size 224 × 224.

### 19. NaN-safe Mean

Creates an array containing `NaN` and calculates its mean using `np.nanmean()`.

### 20. Element-wise and Matrix Multiplication

Demonstrates the difference between `A * B` and `A @ B`.

## Normalization and Standardization

### Normalization

Normalization rescales values to a standard range.

Min-Max normalization formula:

```text
x_scaled = (x - min(x)) / (max(x) - min(x))
```

### Standardization

Standardization transforms data so that it has approximately:

* Mean = 0
* Standard deviation = 1

Formula:

```text
z = (x - mean) / std
```

The notebook also includes a NumPy implementation of normalization and standardization.

## Technologies Used

* Python
* NumPy
* Jupyter Notebook
* Visual Studio Code
* GitHub

## How to Run

Install NumPy using:

```bash
pip install numpy
```

Open `numpy_assignment.ipynb` in Visual Studio Code and run the cells to view the code and outputs.

## Repository Structure

```text
NumPy_assignment/
│
├── README.md
└── numpy_assignment.ipynb
```

All the programs are included in the single `numpy_assignment.ipynb` notebook.

## Purpose

The purpose of this assignment is to practice basic NumPy operations and understand how NumPy is used for numerical computation, array manipulation, data preprocessing, Machine Learning, and image data.
