# World-Happiness-Rankings-2015-2019
What is the happiest country in the world?
Project summary 
This repository contains the code, data and documentation for World Happiness Rankings from 2015 to 2019. This project explores the geography of happiness, examining factors that drive well-being across nations from 2015 to 2019. By using data from the World Happiness Report, this initiative identifies global and regional patterns in happiness scores. With a deep dive on key economic and social factors, and uncovered insights with visualisations that will hopefully help influence dicussion on policy. This reposotory is an easy way to share the code and thoughts throughout this investigation.

## Key Questions
Are there differences in happiness scores between countries with high levels of trust in government? 

Are there any countries that experienced significant increases or decreases in happiness scores between 2015-2019?

Is there a pattern between a country's economic status (GDP per Capita) and its happiness score? Do wealthier countries generally report higher happiness? 

Are there any countries that experienced significant increases or decreases in happiness scores between 2015-2019?

## Data 

https://www.kaggle.com/datasets/unsdsn/world-happiness?select=2015.csv

*2015.csv
*2016.csv
*2017.csv
*2018.csv
*2019.csv

## License
CC0: Public Domain


## Tools 
Commands were written in Python and executed in Jupyter notebooks.

* pandas: For data manipulation and cleaning (DataFrame creation, manipulation, etc.)
* matplotlib.pyplot: For generating basic visualizations (plots, charts).
* seaborn: For creating statistical data visualizations, including advanced charts and plots (e.g., scatterplots, pair plots, categorical plots, heatmaps)
* scikit-learn (sklearn): For machine learning tasks:
    * Normalization/Scaling (MinMaxScaler, StandardScaler)
    * Regression analysis (LinearRegression)
    * Clustering (KMeans)
* folium: For creating interactive maps and performing geospatial analysis
* statsmodels: For conducting statistical tests, including the Dickey-Fuller test for stationarity (time series analysis)
* pmdarima: For Time-series analysis
* os: Path tool to read all local files

## Presentation

Available on [Tableau](https://public.tableau.com/app/profile/vicky.czada/viz/6_7WorldHappinessRankings2015-2019/Story1)

## Limitations:

*   **Data Bias**: The World Happiness Report relies on self-reported data, which can be subjective and culturally influenced.
*   **Temporal Scope**: Analysis is limited to data between 2015 and 2019, potentially missing more recent trends.
*   **Unmeasured Variables**: The analysis does not account for all factors influencing happiness, such as political stability or environmental quality.

## Key findings 
*   Higher GDP per capita is generally associated with higher happiness scores.
*   Trust in government shows a stronger correlation with happiness in Western European countries than in other regions.

## Future work
*   Incorporate qualitative data (e.g., interviews) to gain deeper insights into individual perceptions of happiness.
*   Expand the analysis to include more recent years and explore the impact of global events (e.g., the COVID-19 pandemic).
*   Investigate sub-regional variations in happiness and well-being.
