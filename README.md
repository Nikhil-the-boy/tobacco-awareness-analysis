# Tobacco Usage and Anti-Tobacco Awareness Analysis in Indian States  

This project presents a comprehensive analysis of state-wise tobacco consumption patterns among youth in India, based on data from the Kaggle-hosted Youth Tobacco Survey. The primary objective is to investigate whether exposure to anti-tobacco awareness mediums has a measurable impact on tobacco usage across different regions.

## Project Objectives

- Analyze the prevalence of tobacco usage in rural vs urban populations
- Examine correlations between awareness campaigns and actual tobacco consumption
- Compare patterns of usage against state GDP rankings
- Apply regression modeling to quantify the influence of awareness on behavior

## Key Components

- **Exploratory Data Analysis (EDA):**
  - Identification of missing values, state-level aggregation
  - Comparison between Rural, Urban, and Total population segments
  - Custom visualizations showing awareness vs usage trends

- **Statistical Modeling:**
  - Linear Regression model to assess predictive power of awareness variables on current tobacco usage
  - R² score used to evaluate model performance

- **Data Visualization:**
  - Comparative line plots of usage vs GDP ranking
  - Grouped bar plots highlighting different types of awareness exposure (media, messages, events)
  - Scaled visual overlays to emphasize relative influence

## Data Source

- Dataset: Youth Tobacco Survey in Indian States  
- Source: [Kaggle Dataset](https://www.kaggle.com/datasets/sahilislam007/youth-tobacco-survey-in-indian-states/data)

## How to Use

1. Clone this repository or download the notebook
2. Open `youth_tobacco_survey.ipynb` using Jupyter Notebook or Google Colab
3. Ensure dependencies such as `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, and `numpy` are installed
4. Run cells sequentially to explore the data, visualizations, and regression results

## Results Summary

- The linear regression model yielded a measurable R² score, suggesting a moderate relationship between awareness exposure and actual usage behavior.
- Significant regional variation was observed in both exposure to anti-tobacco messaging and current tobacco usage levels.
- Economic strength (as approximated by GDP rank) appears to correlate inversely with youth tobacco consumption in several states.

## Future Scope

- Incorporate additional models (e.g., decision trees, classification) for deeper insights
- Expand analysis to age, gender, and educational subgroups
- Develop a recommendation engine to suggest the most effective awareness medium by state

## Author

**Nikhil**  
B.Tech Student, IIIT Jabalpur  
Aspiring AI Engineer | Focused on societal impact through data  
