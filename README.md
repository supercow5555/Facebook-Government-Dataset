# Estimating α of the Power-Law Distribution of the Facebook Government Network

## Overview

This project focuses on analyzing the Facebook Government Network to estimate the α of the power-law distribution. The dataset includes 7,057 nodes and 89,455 undirected edges. The primary goal is to utilize network analysis techniques to understand the structure and properties of the network.

## Dataset

The dataset used in this project is the Facebook Government Network, which can be downloaded from [GEMSEC Facebook Dataset](https://snap.stanford.edu/data/gemsec-Facebook.html). It contains:
- 7,057 nodes
- 89,455 undirected edges

## Contents

The project is divided into several key sections:

1. **Data Loading and Verification**
    - Loading the dataset and transforming it into a suitable format for analysis.
    - Verification of the number of nodes and edges.

2. **Degree Distribution Analysis**
    - Calculation and visualization of the degree distribution.
    - Fitting a power-law distribution to the degree distribution.

3. **Estimation of α**
    - Estimation of the power-law distribution parameter α.
    - Visualization of the fitted power-law distribution.

4. **Additional Analyses**
    - Further exploration of network properties.
    - Visualization of other relevant metrics and characteristics.

## Methods

- **NetworkX**: Used for loading and manipulating the network data.
- **Matplotlib**: Employed for creating various visualizations.
- **Power-law Fitting**: Techniques for fitting and estimating the power-law distribution.

## Results

- **Estimated α**: Key findings include the estimated value of α for the power-law distribution.
- **Degree Distribution Visualization**: Graphical representation of the degree distribution and the fitted power-law.

## Usage

1. **Environment Setup**: Ensure you have the necessary Python libraries installed (NetworkX, Matplotlib, etc.).
2. **Data Loading and Preprocessing**: Follow the steps in the notebook to load and preprocess the data.
3. **Running the Analysis**: Execute the provided code to perform the network analysis and estimate α.

## Requirements

- Python 3.x
- NetworkX
- Matplotlib
- Pandas

## Conclusion

This project demonstrates the application of network analysis techniques to understand the structure of the Facebook Government Network and estimate the α parameter of its power-law distribution.

## Acknowledgements

- The SNAP group for providing the dataset.
- The authors of the tools and libraries used in this analysis.
