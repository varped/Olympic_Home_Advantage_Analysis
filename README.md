# Summer-Olympics-Home-Advantage-Analysis
STA 141B Final Project: Analyzing Home Advantage, as well as Subjective vs. Objective Performance Trends in the Summer Olympics (1896–2016)

This repository contains the full analysis of the "Home Field Advantage" in the Summer Olympics. Our study specifically investigates whether host-nation success is more pronounced in judged sports (subjective) compared to timed/measured sports (objective).

## Files
- `Olympic_Home_Advantage_Analysis.ipynb`: The primary Jupyter Notebook containing the Kaggle API integration, data cleaning, feature engineering, and statistical visualizations.
- `Cleaned_Summer_Olympics_Dataset`: The cleaned dataset used for the Project Analysis. https://drive.google.com/file/d/1XDfMgdT21DdeBJultCQ7cOsvhlbcX0_1/view?usp=sharing
- `olympic_host_intensity.html`: A Folium-based visualization showing historical host nations and their relative performance boosts. https://varped.github.io/Olympic_Home_Advantage_Analysis/olympic_host_intensity.html
- `Public Dataset (Olympics Dataset from Kaggle)`: https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results/data

## How to Run the Code
You can run the notebook by following these steps:
- API Key: Generate a kaggle.json at Kaggle Settings (see Auth Guide): https://github.com/Kaggle/kaggle-cli/blob/main/docs/README.md#authentication
- Download the Notebook:
Click on Olympic_Home_Advantage_Analysis.ipynb in this repository and download the file to your computer.
- Open Jupyter Notebook or Jupyter Lab
- Navigate to the downloaded .ipynb file
- Input your API token in the first cell (folllow the comments)
- Run all cells in order to reproduce the full analysis and predictions.

## Proficiency of Topics
- Web Scraping, Visualization (Folium), Pandas, Stats Model (Logit Regression)
