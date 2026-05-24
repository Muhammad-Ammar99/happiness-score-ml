# World Happiness Score Predictor

A data analysis and machine learning project that explores the World Happiness Report dataset, visualizes key happiness factors, and predicts a country's happiness score using Linear Regression.

##  Features

- Exploratory Data Analysis (EDA) with bar charts, scatter plots, and stacked charts
- Correlation analysis between happiness score and individual factors
- Linear Regression model to predict happiness scores
- Interactive input to predict and rank a custom country's happiness score

##  ML Model

- **Algorithm:** Linear Regression (scikit-learn)
- **Features:** Economy, Family, Health, Freedom, Generosity, Corruption, Dystopia, Job Satisfaction
- **Target:** Happiness Score

##  Dataset

Uses the `World Happiness Report.csv` dataset. Place it in your working directory before running.

##  Getting Started

1. Clone the repo
2. Install dependencies: `pip install pandas numpy matplotlib scikit-learn`
3. Add the dataset CSV to your working directory
4. Open `happinessratio.ipynb` in Jupyter or Google Colab and run all cells

##  Results

The model achieves a high R² score due to strong correlations between Job Satisfaction/Economy and the Happiness Score — note this may indicate overfitting. Consider dropping those features for a more generalizable model.

##  Tech Stack

Python · Pandas · NumPy · Matplotlib · Scikit-learn
