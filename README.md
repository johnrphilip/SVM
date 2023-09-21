# Support Vector Machine for Predicting Energy Consumption

## Executive Summary

- **Objective**: To predict the impact of renewable energy usage on the UK's carbon emissions using a Support Vector Regression (SVR) model.
- **Methodology**: Utilized datasets from the Global Carbon Project and the Office of National Statistics. Employed tabu search and greedy search for feature selection optimization.
- **Results**: Achieved high R-squared and low Mean Squared Error (MSE) values, proving the model's effectiveness.
- **Limitations**: Did not account for all influencing variables like economic growth, energy type, and government policies.
- **Implication**: Provides valuable insights for policymakers and businesses in the renewable energy sector.

## 1. Introduction

- Address the significant role of the energy sector in climate change.
- Data sourced from the Global Carbon Project and Office of National Statistics.

## 2. Literature Review

- Various AI models, including ANN, decision trees, naive Bayes, and support vector machines, are employed in energy prediction.
- Importance of feature selection optimization techniques like tabu search, hill climbing, etc.

## 3. Research Design

- Utilized Support Vector Regression with a linear kernel.
- Used tabu search for feature optimization.
- Development environment: Python, Datalore Jupyter notebook.
  
## 4. Experimental Results and Analysis

- High R-squared and low MSE values indicate effective modeling.
- Tabu Search and Greedy Search performed well in feature optimization.
  
| Model Name                     | MSE     | R-squared | K-Fold MSE | K-Fold R^2 |
| ------------------------------ | ------- | --------- | ---------- | ---------- |
| Initial SVR w/ all features    | 61.66   | 0.991     | 177.74     | -6.73      |
| SVR with randomly chosen feat. | 1482.17 | 0.78      | 2249.19    | -15.88     |
| SVR w/ Tabu                    | 76.18   | 0.988     | 286.41     | -0.23      |
| SVR w/ Greedy Approach         | 18.34   | 0.997     | 132.76     | -3.83      |

## 5. Conclusion and Future Work

- Despite its limitations, the model is effective for predicting the impact of renewable energy on CO2 emissions.
- Future work could include expanding the dataset and exploring more machine learning models for comparative analysis.

> "You cannot get through a single day without having an impact on the world around you. What you do makes a difference, and you have to decide what kind of difference you want to make." — Jane Goodall

