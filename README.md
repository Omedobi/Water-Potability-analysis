# Water Quality Analysis and Classification
This repository contains code for analyzing water quality data and performing classification tasks based on water potability. The code utilizes various Python libraries, including matplotlib, pandas, seaborn, numpy, scipy, sklearn, and pycaret.

## Data Analysis and Visualization
The code begins by loading a dataset from a CSV file and preparing the data for analysis. Missing values are dropped, and descriptive statistics are calculated to gain insights into the dataset.

Next, the code visualizes the distribution of safe and unsafe water potability using histograms. It also examines the impact of several factors, such as pH, hardness, total dissolved solids (TDS), chloramines, sulfate, conductivity, organic carbon, trihalomethanes, and turbidity, on water quality.

## Statistical Analysis
Statistical analysis is performed to determine the correlation between different variables. The code calculates the Pearson correlation coefficient and p-value between the "Solids" and "Potability" columns. Additionally, it evaluates the correlation between all columns in the dataset.

## Machine Learning and Classification Modeling
The code demonstrates the application of machine learning techniques to predict water potability based on turbidity. A linear regression model is trained and evaluated using the sklearn library. Additionally, the code employs the pycaret library for classification tasks. It sets up the data, compares various classification models, and creates Extra Trees and Random Forest classifiers to predict water potability.

Please note that this code assumes the necessary libraries are installed and the dataset is provided in a CSV file named "water_potability.csv".

## Usage
To run the code and perform water quality analysis and classification tasks, follow these steps:

## Clone this repository to your local machine.
Ensure that the required libraries are installed by running pip install -r requirements.txt.
Place the dataset file named "water_potability.csv" in the same directory.
Run the code in your preferred Python environment or editor.
Explore the generated visualizations and analyze the results obtained.# Water-Potability-analysis
