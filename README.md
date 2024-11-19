# Breast Cancer Diagnosis Prediction

## Overview

This repository contains code for training a machine learning model to predict whether a cell is malignant or not based on its measurements. The dataset used for this project includes detailed measurements of various characteristics of cells along with their diagnosis (malignant or not).

## Dataset

The dataset consists of the following columns:

- `id`: Unique identifier for each cell
- `diagnosis`: Diagnosis of the cell (malignant or not)
- `radius_mean`: Mean of distances from center to points on the perimeter
- `texture_mean`: Standard deviation of gray-scale values
- `perimeter_mean`: Mean size of the core tumor
- `area_mean`: Mean area of the core tumor
- `smoothness_mean`: Mean of local variation in radius lengths
- `compactness_mean`: Mean of perimeter^2 / area - 1.0
- `concavity_mean`: Mean severity of concave portions of the contour
- `concave points_mean`: Mean number of concave portions of the contour
- `symmetry_mean`: Mean symmetry
- `fractal_dimension_mean`: Mean "coastline approximation" - 1
- `radius_se`: Standard error of the mean of distances from center to points on the perimeter
- `texture_se`: Standard error of gray-scale values
- `perimeter_se`: Standard error of the size of the core tumor
- `area_se`: Standard error of the area of the core tumor
- `smoothness_se`: Standard error of local variation in radius lengths
- `compactness_se`: Standard error of perimeter^2 / area - 1.0
- `concavity_se`: Standard error of severity of concave portions of the contour
- `concave points_se`: Standard error for number of concave portions of the contour
- `symmetry_se`: Standard error for symmetry
- `fractal_dimension_se`: Standard error for "coastline approximation" - 1
- `radius_worst`: Worst or largest mean value for radius
- `texture_worst`: Worst or largest mean value for texture
- `perimeter_worst`: Worst or largest mean value for perimeter
- `area_worst`: Worst or largest mean value for area
- `smoothness_worst`: Worst or largest mean value for smoothness
- `compactness_worst`: Worst or largest mean value for compactness
- `concavity_worst`: Worst or largest mean value for concavity
- `concave points_worst`: Worst or largest mean value for concave points
- `symmetry_worst`: Worst or largest mean value for symmetry
- `fractal_dimension_worst`: Worst or largest mean value for fractal dimension
- `Unnamed: 32`: Unnamed column

## Approach

The goal is to train a machine learning model using this dataset to predict whether a given cell is malignant or not based on its measurements. Several classification algorithms will be explored and evaluated for their performance.

## Repository Structure

- `data/`: Directory to store the dataset.
- `notebooks/`: Directory containing Jupyter notebooks for data exploration, preprocessing, and model training.
- `models/`: Directory to save trained machine learning models.
- `src/`: Directory containing source code for data preprocessing, model training, and evaluation.
- `README.md`: This file provides an overview of the project.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook (for running the notebooks)

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/Mariambadra/BC_melignancy_prediction.git
