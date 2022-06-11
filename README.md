# Data_Analysis

### Sports (Football) Data Analyze and Visualization
- Height and weight are converted to meters and kg respectively, Alias used in 'Skill Moves' attribute to make it more readable, players are grouped into defender, midfielder or forward according to their positions (E.g. CDM (central defender midfielder) ==> midfielder)
- Average height and weight by position groups are visualized on scatter plot
- Jersey numbers are investigated with horizontal bar graph to see their preferences by each position group
- Sum of player salaries of teams are sorted and divided into position groups along with the average salary line
- Parameter is created to dynamically filter top (1/5/10/20) wage paying clubs and visualized their stadium locations on the spatial map
- Set is created through 'Nationality' attribute to see top 20 countries with the most wage earning players along with it's crossmap
- Created a interactive dashboard from 'map of top earning countries by player wage' and it's crosstab using the actions property
- Top 10 earning players by position are found (Table calculation is used on index to filter top 10 values)
- Players with top release clause are sorted within age bins (5 year intervals) and their market values are underlined

### E-Commerce Analytics  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13oqEnVJSmPkopm5kMOfuygSqoBv1iDbZ?usp=sharing)
- EDA and preprocessing: E-commerce dataset will be analyzed and processed for next steps.
- Cohort and Retention Analysis: Conduct cohort analysis and find out monthly retention rates.
- Recency, Frequency, Monetary (RFM): Customers of an online retailer will be classified into clusters based on transactions over a year.
- Customer Lifetime Value (CLTV): Find out expected transactions, revenues from customers and their lifetime values to the retailer.
- Time-series analysis: Forecasting revenue for next month.

### Sales Time-series Forecasting  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/149vX62kSWqNCoJ_I5LTcmCXaY7vIQErj?usp=sharing)
- EDA and Pre-processing: Sales dataset is analyzed and processed for next steps. Stationarity of the series is checked with ADF and KPSS tests.
- Classical Time-series models: ACF and PACF graphs of the series are investigated. ARIMA(2,0,3), Auto-ARIMA and Holt-Winters models are implemented on the series and their performances are compared vs test set.
- Machine Learning and Feature Engineering on Time-series: Impact of features such as store information, holidays etc. are analyzed. Random forest regression model with various set of features is implemented then its' performance is compared with classical-time series models and the test set.
- In conclusion, ARIMA outperforms other models. Even though feature engineering helps to improve performance in random forest regression, this model has still higher error compared to classical time-series models.
