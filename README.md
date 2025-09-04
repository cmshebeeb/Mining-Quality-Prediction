# Mining-Quality-Prediction

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

## Tools
- **Google Colab**: For data analysis and model building.
- **Python Libraries**: pandas, scikit-learn, matplotlib.
