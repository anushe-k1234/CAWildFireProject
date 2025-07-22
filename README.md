# CAWildFireProject
Data Science/Analytics Project Using CA Wildfire Data

## Project Summary

• Analyzed California wildfire data from multiple sources including fire incidents, weather, and socioeconomic factors.  
• Explored wildfire trends, spatial patterns, and seasonal effects using maps, clustering, and statistical tests.  
• Built predictive models for fire size, mega fire classification, and damage cost estimation using Random Forest, XGBoost, and linear regression. 
• Evaluated model performance with metrics such as R², precision, recall, ROC-AUC, and visualized results with plots.  
• Conducted statistical tests to compare fire causes and examine fire size differences by season.

## Project Structure

- 01_data_preparation.ipynb  
  Loads and cleans raw wildfire, weather, and socioeconomic data; performs feature engineering.

- 02_eda_visualization.ipynb  
  Performs exploratory data analysis with time series, maps, and clustering to understand fire patterns.

- 03_modeling_predictions.ipynb  
  Develops machine learning models for predicting fire size, classifying mega fires, and estimating damage costs.

- 04_results_figures_report.ipynb  
  Summarizes findings, reports model performance, and presents statistical test results.

## Dataset

Datasets used include:  

- Fire incident records with fire perimeters and cause data  
- Daily weather data with temperature, wind, and precipitation  
- Socioeconomic and built environment risk indicators by county  
- California county shapefiles for spatial joins and mapping  

## Model Details

- Fire size prediction: Random Forest Regressor (R² = 0.956)  
- Mega fire classification: Random Forest and XGBoost classifiers (ROC-AUC = 1.00, but low recall due to class imbalance)  
- Damage cost estimation: Linear Regression and XGBoost regression (XGBoost R² = 0.999)  

## Outputs

- Predictive model performance metrics and plots  
- Statistical test results comparing fire causes and seasonal fire sizes  
- Data merges and feature-engineered datasets saved as CSV  
- Visualizations including ROC curves, precision-recall curves, and residual plots  

## Key Findings

- Wildfires have increased in frequency and size, with longer fire seasons.  
- Human-caused fires tend to cause higher economic losses than lightning-caused fires.  
- Climate variables like temperature and wind speed strongly influence fire size.  
- Damage cost depends more on built environment and population density than just fire size.  
- Mega fires are rare, making them difficult to detect accurately with current models.  
- Statistical tests show significant differences in losses by fire cause and fire size distributions by season.  

## Limitations

- Missing or inconsistent data in fire perimeters and damage estimates.  
- Highly imbalanced classes for mega fire classification reduce model recall.  
- Historical data may not capture future wildfire risks under climate change.  
