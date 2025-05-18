# Fantasy-Premier-League-Points-Predictor
Trained ML models on 600+ players to predict FPL performance. Used regression models with EDA storytelling.
---
## Data Acquisition & Cleaning
- **Scraping**: Data scraped from the official FPL website (7th October 2024) using `requests` and `BeautifulSoup`.
- **Cleaning**: Removed duplicates, handled nulls, standardized formats.
- **Feature Engineering**: Derived new features such as:
  - Points per 90 minutes
  - Attack/Defense efficiency scores
  - Form indicators
---
## Analysis & Reporting (Tableau / Power BI)

- Created **team and player dashboards** showcasing:
  - Player rankings by position
  - Team-wise point distribution
  - Position-wise performance heatmaps
-  Built for strategic fantasy decisions and comparisons
---
## EDA & Statistical Testing

- **Trend Analysis**:
  - Season-wise points, performance over time
  - Position & team-based trends
- **Correlation & Outlier Detection**
- **Statistical Tests**:
  - ANOVA: To analyze variance across multiple positions
  - T-Test: To compare top-tier vs mid-tier players
  - Chi-square: For categorical dependencies
  - Mutual Information: For feature relevance
---
## Feature Selection

- **Filter Methods**: Correlation, Variance Threshold
- **Wrapper Methods**: Recursive Feature Elimination (RFE)
- **Embedded Methods**: Feature importance from tree-based models
---
## Modeling

- **Baseline Models**:
  - Linear Regression
  - Decision Tree
  - K-Nearest Neighbors
- **Advanced Modeling (via PyCaret)**:
  - Random Forest
  - XGBoost
  - Ensemble Models
---
## Hyperparameter Tuning

- Applied **GridSearchCV** and **PyCaret’s AutoML** features for optimal parameters.
- Evaluated models using metrics like R², RMSE, MAE across training and validation sets.
---
## Web Development & Hosting

- Built an interactive web app using **Streamlit** for:
  - Player selection predictions
  - Position-wise comparison
  - Model summary and insights
- [FPL Points Predictor](https://huggingface.co/spaces/shimona02/FPLPredictor)
---
## Next Steps

- Automate weekly data scraping and model updates
- Add team formation recommender system
---
## Conclusion

This project demonstrates a **full data pipeline** — from scraping raw data to statistical analysis, ML modeling, and visualization. It combines both **technical expertise and domain knowledge** in football analytics to provide actionable insights.
---
## Who Will Benefit

- **Fantasy Premier League Managers**: For smarter weekly picks
- **Football Enthusiasts**: To understand player performance
- **Data Science Recruiters**: Demonstrates end-to-end project lifecycle
- **Sports Analytics Firms**: A strong sample for predictive analytics in sports
---
### Connect with me

- GitHub: [GitHub](https://github.com/KARANKHADKA)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/karan-khadka-185547230/)

