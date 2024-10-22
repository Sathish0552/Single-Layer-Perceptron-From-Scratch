Single Layer Perceptron from Scratch for Wine Classification
This project implements a Single Layer Perceptron (SLP) to classify different types of wine using the UCI Wine Dataset. The goal is to predict the wine type based on several features such as alcohol content, malic acid levels, ash, and more.

Table of Contents
Introduction
Dataset
Project Structure
Prerequisites
Installation
Usage
Results
Contributing


Introduction
This project utilizes a Single Layer Perceptron (SLP), a type of artificial neural network, to classify wine into one of three categories. The dataset used for this project includes chemical analysis of 13 different attributes of wine grown in the same region in Italy but derived from three different cultivars.

Dataset
The dataset is the UCI Wine dataset, which consists of 178 samples of wine with 13 features each and a class label indicating the type of wine.

Features:
Alcohol
Malic Acid
Ash
Alcalinity of Ash
Magnesium
Total Phenols
Flavanoids
Nonflavanoid Phenols
Proanthocyanins
Color Intensity
Hue
OD280/OD315 of diluted wines
Proline
Label: The wine type (1, 2, or 3).
Project Structure
bash
Copy code
.
├── wine.csv                     # The dataset file
├── SLP.py                       # Main script for training and testing the perceptron
├── README.md                     # Project documentation
└── requirements.txt              # Python dependencies


Prerequisites
To run this project, you will need to have Python 3.x installed along with the necessary libraries. 
The main libraries used are:
numpy
pandas
scikit-learn
matplotlib
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/Sathish0552/Single-Layer-Perceptron.git
cd Single-Layer-Perceptron
Install the dependencies:

bash
Copy code
pip install -r requirements.txt
Ensure you have the dataset (wine.csv) placed in the project root directory.

Usage
You can run the perceptron model on the wine dataset by executing the following command:

bash
Copy code
python SLP.py
The script will:

Load the dataset from wine.csv.
Shuffle the dataset.
Train the perceptron model on a training set.
Test the model on the test set and output the accuracy.
Results
The results of the perceptron model will be displayed in the terminal, showing the accuracy of the classification. In addition, the covariance and correlation matrices of the dataset will be generated as part of the exploratory data analysis.

Contributing
If you want to contribute to this project, feel free to fork the repository and submit a pull request. We welcome any improvements and bug fixes!

