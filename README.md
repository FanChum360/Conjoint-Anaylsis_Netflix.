# __Conjoint Analysis of Streaming Services__

This project performs a conjoint analysis to understand consumer preferences for various streaming service features. The analysis evaluates trade-offs among attributes such as content types and platform offerings, helping to determine which combinations of features are most valued by users.

## Project Overview

In this project, we examine user preferences for services similar to Netflix, including:
HBO
Marvel
Disney
Prime Originals
Soccer (sports content)
By analyzing how consumers value different features, the project aims to provide insights for optimizing streaming service bundles and improving product offerings.

## Key Features

Conducted a conjoint analysis to determine attribute importance and utility scores.
Visualized results using bar charts, treemaps, and other plots.
Built entirely in Python, using Jupyter Notebooks and Google Colab for development and experimentation.

## Tools & Libraries

Python 3.7
Jupyter Notebook / Google Colab
pandas – for data manipulation
numpy – for numerical computations
statsmodels – for regression analysis and estimating utilities
matplotlib – for plotting charts
squarify – for creating treemaps

## Methodology

1. Data Preparation:
Defined streaming service attributes and levels.
Created a dataset representing different service combinations.
2. Conjoint Analysis:
Used linear regression models to estimate part-worth utilities for each attribute.
Calculated importance scores to determine which features most influence user preferences.
3. Visualization:
Plotted utility scores and feature importance for easy interpretation.
Generated treemaps to show relative contribution of each feature to overall preference.

## Example Visualizations

#### Bar Graph
<img width="645" height="374" alt="Screenshot 2026-01-12 at 2 26 07 PM" src="https://github.com/user-attachments/assets/7e9516e9-966c-4b5a-b04d-bbcd97ea63f2" />

#### Lollipop Plot
<img width="637" height="332" alt="Screenshot 2026-01-12 at 2 27 39 PM" src="https://github.com/user-attachments/assets/b62af573-3be0-4678-8cbf-d15a33727e9a" />

#### Tree Map


<img width="538" height="407" alt="Screenshot 2026-01-12 at 2 28 36 PM" src="https://github.com/user-attachments/assets/adc8b483-4d49-4059-8199-ebb446617f28" />




## How to Run

1. Clone the repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install required libraries if not already installed:
pip install pandas numpy statsmodels matplotlib squarify
4. Run the notebook cells sequentially to reproduce the analysis.

## Outcomes

Identified which streaming service attributes users value most.
Provided insights that could guide content bundle offerings and marketing strategies.
Demonstrated how Python and statistical modeling can effectively support product design decisions.

## License

This project is open-source and available under the MIT License.
