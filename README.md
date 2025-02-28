# Project Title: Solubility Prediction Analysis

## Description
This project involves the analysis and prediction of solubility using various molecular descriptors. The dataset used includes molecular properties such as MolLogP, MolWt, NumRotatableBonds, AromaticProportion, and logS. The analysis process includes data cleaning, outlier detection, univariate analysis, and multivariate analysis.

## Installation
To run this project, you need to have the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn

You can install these libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/chandrakant1212/chandrakant1212.git
```
2. Navigate to the project directory:
```bash
cd chandrakant1212
```
3. Open the Jupyter Notebook:
```bash
jupyter notebook Assignment1_final.ipynb
```
4. Run the cells in the notebook to perform the analysis.

## Analysis Steps
1. **Data Cleaning**:
   - Display initial dataset and check for missing values.
   - Fill missing values with the median of each column.
2. **Outlier Detection**:
   - Use z-scores and IQR to identify and handle outliers.
3. **Univariate Analysis**:
   - Generate histograms, box plots, and violin plots for visualizing distributions.
   - Calculate skewness and kurtosis for each variable.
4. **Multivariate Analysis**:
   - Calculate and visualize the correlation matrix.
   - Generate pair plots to identify relationships between variables.

## Results
The analysis provides insights into the distribution and relationships of molecular descriptors, which can be used for predicting solubility.

## Author
Chandrakant1212.
