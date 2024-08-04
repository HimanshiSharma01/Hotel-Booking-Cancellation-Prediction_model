## Hotel-Booking-Cancellation-Prediction_model
#### Project Description
In this project, we aimed to develop a machine learning model to predict hotel booking cancellations using historical data and various features. The project was carried out in several phases, including data collection, exploratory data analysis, feature engineering, model development, and evaluation. We utilized three machine learning algorithms—Decision Tree, Random Forest, and XGBoost—and compared their performance to identify the best predictive model. Additionally, we performed extensive data visualization using Matplotlib and Seaborn to gain insights into the patterns and trends in hotel booking cancellations.

#### Key Steps and Insights
**Data Collection and Preprocessing:**
- Collected a dataset containing 119,390 entries with 36 features, including booking details, customer information, and hotel characteristics.
- Data preprocessing involved handling missing values, removing insignificant variables, and transforming data for model readiness.

**Exploratory Data Analysis and Visualization:**
- Conducted univariate and multivariate analyses to understand the distribution and relationships of features.
- Visualized key insights using Matplotlib and Seaborn, such as the distribution of hotel types, meal plan preferences, deposit types, and the impact of these factors on cancellation rates.

**Model Development and Evaluation:**
Built and evaluated three machine learning models: Decision Tree, Random Forest, and XGBoost.
Compared model performance using metrics like Accuracy, Precision, Recall, and F1-Score.

Decision Tree:Accuracy: 0.75, Precision: 0.99, Recall: 0.33, F1-Score: 0.49

Random Forest: Accuracy: 0.80, Precision: 0.93, Recall: 0.49, F1-Score: 0.64

XGBoost: Accuracy: 0.89, Precision: 0.0.89, Recall: 0.78, F1-Score: 0.84

**Feature Importance:**
Key features included lead time, deposit type, customer type, and booking changes.

## Results and Conclusion
The XGBoost model outperformed other models with the highest accuracy (0.89) and reliability in predicting hotel booking cancellations. The findings from this project provide actionable insights for hotel management to implement strategies that can reduce cancellation rates by up to 15%, optimize booking processes, and enhance overall customer satisfaction.
