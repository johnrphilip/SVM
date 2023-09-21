# Executive Summary

This project aims to analyze the impact of renewable energy usage on CO2 emissions in the UK. Utilizing datasets from the Office of National Statistics and the Global Carbon Project, we've built a Support Vector Regression (SVR) model to predict CO2 emissions based on various energy sources. The model employs optimization techniques like Tabu Search and Greedy Search for feature selection and is validated through metrics like R-squared and Mean Squared Error (MSE).

## What I Learned & Skills Demonstrated

- **Data Preprocessing**: Handling different units, managing missing data, and nominal attributes.
- **Exploratory Data Analysis**: Utilizing statistical and visual methods to understand the essence of the data.
- **Machine Learning**: Developed a Support Vector Regression (SVR) model for prediction.
- **Optimization Techniques**: Employed Tabu Search and Greedy Search for feature selection.
- **Statistical Analysis**: Used R-squared and MSE for model evaluation, and employed K-fold cross-validation for robust validation.
- **Data Visualization**: Used Python libraries like Matplotlib and Seaborn for graphical representation.
- **Programming**: Python, Pandas, NumPy, Matplotlib, Scikit-learn.

## Sections

### Introduction
Provides a context to the urgency of addressing climate change and sets the stage for the study.

### Literature Review
Explores existing models and techniques in energy prediction, focusing on the utility of Support Vector Machines (SVM) in this domain.

### Research Design
Outlines the methodology, including the SVR model and the optimization techniques used for feature selection.

### Experimental Results and Analysis
Discusses the model's performance based on various metrics and compares different optimization techniques.


  
| Model Name                     | MSE     | R-squared | K-Fold MSE | K-Fold R^2 |
| ------------------------------ | ------- | --------- | ---------- | ---------- |
| Initial SVR w/ all features    | 61.66   | 0.991     | 177.74     | -6.73      |
| SVR with randomly chosen feat. | 1482.17 | 0.78      | 2249.19    | -15.88     |
| SVR w/ Tabu                    | 76.18   | 0.988     | 286.41     | -0.23      |
| SVR w/ Greedy Approach         | 18.34   | 0.997     | 132.76     | -3.83      |

### Business Challenge
Explains the practical applications of the predictive model in real-world scenarios.

### Limitations
Identifies the challenges and limitations faced during the research.

### Conclusion
Summarizes the findings and suggests future lines of investigation.

## 5. Conclusion and Future Work

- Despite its limitations, the model is effective for predicting the impact of renewable energy on CO2 emissions.
- Future work could include expanding the dataset and exploring more machine learning models for comparative analysis.

> "You cannot get through a single day without having an impact on the world around you. What you do makes a difference, and you have to decide what kind of difference you want to make." — Jane Goodall

