# Mining-Quality-Prediction

## Certificate
[Internship Certificate](https://drive.google.com/file/d/1TzdeJDjH-uioOjd7iOHvxdoJG1sVIjuK/view?usp=drive_link)

## Project Overview
This project aims to predict the percentage of silica (% Silica Concentrate) in iron ore concentrate from a mining flotation process using machine learning regression. The goal is to help engineers improve ore quality, reduce waste, and minimize environmental impact by predicting silica levels accurately.

## UniConverge Technologies
UniConverge Technologies focuses on industrial IoT and machine learning for manufacturing efficiency. This project aligns with their mission to optimize industrial processes using data-driven solutions.

## Dataset
- **Source**: Flotation plant data (March-September 2017), 737,453 rows, 24 columns.
- **Key Columns**:
  - Date: Timestamp of data collection.
  - % Iron Feed, % Silica Feed: Initial ore quality.
  - Starch Flow, Amina Flow, etc.: Process measurements (flows, pH, density).
  - Flotation Column 01-07 Air Flow/Level: Machine conditions.
  - % Silica Concentrate: Target to predict.
- **Link**: [Google Drive](https://drive.google.com/file/d/1N80d8eTDAf1JMQXGQbHDAUaMGRyA8QG3/view?usp=sharing)

## Project Questions
- Can % Silica Concentrate be predicted every minute?
- How many hours ahead can % Silica be predicted?
- Can % Silica be predicted without using % Iron Concentrate (due to high correlation)?

## Repository Structure
- `/data`: Placeholder for dataset (not uploaded due to size).
- `/notebooks`: For Google Colab .ipynb files.
- `/reports`: For final project report and visuals.

## Model Plan
1. Load dataset from Google Drive using pandas.
2. Fix missing values (if any) and convert columns to correct data types.
3. Use Linear Regression to predict % Silica Concentrate.
4. Test model accuracy with RMSE and MAE.

## Tools
- **Google Colab**: For data analysis and model building.
- **Python Libraries**: 
  - pandas (data handling)
  - scikit-learn (regression models)
  - matplotlib (plots)
## Skills Demonstrated
- Python
- Machine Learning
- Data Cleaning
- Random Forest
- Visualization
