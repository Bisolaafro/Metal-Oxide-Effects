# Metal Oxide Concentrations and Weather Conditions in an Italian City

## Project Overview

This project aims to analyze the relationship between metal oxide concentrations in the air and various weather conditions, including temperature, relative humidity, and absolute humidity, in an Italian city. Through data cleaning, visualization, and machine learning techniques, we investigated whether these metal oxides have a significant impact on the city's weather conditions.

## Data Cleaning

To ensure the accuracy and reliability of our analysis, we performed several data cleaning steps:
- **Removing Missing Values:** We eliminated any rows with missing data to maintain the integrity of our dataset.
- **Date Conversion:** Provided dates were converted to `DateTime` format for proper temporal analysis.
- **Numerical Conversion:** Numerical data was converted to appropriate formats for accurate calculations.

## Data Visualization

Using the data visualization techniques learned in the course, we created various plots to explore the relationships between the features:
- **Heatmap:** To identify correlations between features, we generated a heatmap. We found that temperature, relative humidity, and absolute humidity did not have a strong correlation with metal oxide concentrations.
- **3-D Scatter Plot:** This visualization further confirmed the lack of significant correlation between these features.

## Machine Learning Analysis

We employed several machine learning techniques to further investigate the relationships:
- **Linear Regression and K-Fold Cross Validation:** We used these methods to determine if there was a relationship between metal oxide concentrations and weather conditions. The linear regression model indicated a potential correlation with absolute humidity, as it had the highest training and validation scores.
- **DecisionTreeClassifier and KNNClassifier:** These classifiers provided high training and testing scores, suggesting that our models effectively generalize the relationship between metal oxide concentrations and weather conditions for both the given dataset and new data in this city.

## Conclusions

Based on our analysis, we concluded that:
- There is minimal evidence to suggest that metal oxide concentrations significantly affect temperature, relative humidity, and absolute humidity in this Italian city.
- The city is heavily polluted, and other factors may play a significant role in its environmental and weather conditions. Therefore, additional information about the city is necessary to make more concrete conclusions about the true effects of these metal oxide concentrations on the weather.

## Future Work

For a more comprehensive understanding of the relationship between metal oxides and weather conditions, future work could include:
- Gathering more detailed environmental data from the city.
- Exploring other potential factors influencing the weather conditions.
- Applying more advanced machine learning techniques to refine our models.

By continuing to investigate these relationships, we can gain deeper insights into the environmental dynamics of this Italian city and potentially develop more effective strategies for mitigating pollution and its impacts on weather conditions.
