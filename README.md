# Single Layer Perceptron from Scratch for Wine Classification

This project implements a Single Layer Perceptron (SLP) to classify different types of wine using the UCI Wine Dataset. The goal is to predict the wine type based on several features.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction
This project utilizes a Single Layer Perceptron (SLP), a type of artificial neural network, to classify wine into one of three categories based on chemical analysis.

## Dataset
The dataset is the UCI Wine dataset, consisting of:
- **Samples**: 178
- **Features**: 13 attributes including:
  - Alcohol
  - Malic Acid
  - Ash
  - Alcalinity of Ash
  - Magnesium
  - Total Phenols
  - Flavanoids
  - Nonflavanoid Phenols
  - Proanthocyanins
  - Color Intensity
  - Hue
  - OD280/OD315 of diluted wines
  - Proline
- **Label**: Wine type (1, 2, or 3)

## Project Structure
├── wine.csv # The dataset file ├── SLP.py # Main script for training and testing the perceptron ├── README.md # Project documentation └── requirements.txt # Python dependencies


## Prerequisites
To run this project, you will need:
- Python 3.x
- Necessary libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Sathish0552/Single-Layer-Perceptron.git
   cd Single-Layer-Perceptron
2.Install the dependencies:
   pip install -r requirements.txt
3.Ensure you have the dataset (wine.csv) placed in the project root directory.

Usage
To run the perceptron model on the wine dataset, execute:
python SLP.py
The script will:

Load the dataset from wine.csv
Shuffle the dataset
Train the perceptron model on a training set
Test the model on the test set and output the accuracy
Results
The results of the perceptron model will be displayed in the terminal, showing the classification accuracy. Covariance and correlation matrices of the dataset will also be generated as part of the exploratory data analysis.

Contributing
If you want to contribute to this project, feel free to:

Fork the repository
Submit a pull request
We welcome any improvements and bug fixes!

You can copy this entire block and paste it into your `README.md` file. Let me know if you need any more help!
