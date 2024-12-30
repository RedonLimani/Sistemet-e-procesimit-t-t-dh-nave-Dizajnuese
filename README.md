# Sistemet e procesimit te te dhenave dizajnuese

## Project Overview
This project involved designing a data processing system to predict patient mortality based on a rich dataset. Our workflow included data collection, exploratory data analysis (EDA), and predictive modeling. Additionally, we enriched our dataset by web scraping metadata to obtain descriptions for all variables, ensuring clarity and context for the analysis.

## Dataset
We used a dataset from [Kaggle](https://www.kaggle.com/datasets/mitishaagarwal/patient/data) containing **85 columns** of data. The dataset included a wide range of variables relevant to patient health and treatment outcomes.

### Dataset Enrichment
To provide better insights into the dataset, we implemented a **web scraping script** to collect descriptions for all columns. This step ensured that we fully understood the data and its implications in the context of patient mortality prediction.

## Exploratory Data Analysis (EDA)
EDA was performed using **Tableau**, allowing us to generate interactive visualizations. Key insights from this process included:
- Trends in patient demographics and health outcomes.
- Correlations between specific variables and mortality rates.


### Examples of Visualizations
1. **Mortality Rate by Age Group and Gender**: Highlighted how age and gender impacts patient outcomes.
2. **Variable Correlation**: Showcased relationships between critical health metrics.

## Predictive Modeling
The primary objective was to predict whether a patient would survive or not. Steps included:
1. **Data Preprocessing**: Cleaning, handling missing values, and feature selection.
2. **Modeling**: The ML model of choice for this project is KNN

## Tools & Technologies
- **Kaggle**: Dataset source.
- **Python**: Data preprocessing, modeling, and web scraping.
- **Tableau**: Interactive visualizations for EDA.
- **BeautifulSoup**: For web scraping variable descriptions.
- **sklearn**: ML modeling.

## Challenges and Solutions
- **High Dimensionality**: Addressed using feature engineering and reduction techniques.
- **Missing Data**: Managed using imputation strategies and domain knowledge.
- **Interpretability**: Web scraping for metadata and visualizing relationships improved the interpretability of the results.


## Future Work
- UI for inputing patient attributes and returning likleyhood of mortality.

## License
This project is released under [The Unlicense](https://unlicense.org/), which places the work in the public domain. Feel free to use, modify, or distribute it as you see fit.

