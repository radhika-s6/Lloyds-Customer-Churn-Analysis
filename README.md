📌 **Project Overview**

The project focuses on applying data science techniques to analyse customer behaviour and build a predictive model to identify customers at risk of leaving the bank (customer churn).

The objective was to help the analytics team at SmartBank, a subsidiary of Lloyds Banking Group, better understand customer behaviour and develop data-driven strategies to improve customer retention. 


🎯 **Business Problem**

Customer churn represents a major challenge for financial institutions. Losing customers to competitors reduces revenue and market share.

The goal of this project was to:

📊 Analyse customer behaviour using structured data
🔍 Identify patterns associated with customer churn
🤖 Build a predictive machine learning model to detect at-risk customers
💡 Provide actionable insights to support customer retention strategies

The project simulates the work of a data science graduate within the Data Science & Analytics team at Lloyds Banking Group. 


🗂️ **Project Structure**

The project was completed in two key phases.

📊 **Task 1 – Data Exploration & Preparation**

The first phase focused on understanding the available data and preparing it for modelling.


📁 Data Sources

Multiple datasets were combined using a unique CustomerID, including:

👥 Customer demographics
💳 Transaction history
🛠️ Customer service interactions
🌐 Online activity data
🚪 Customer churn status

These datasets capture behavioural, engagement, and service-related factors that may influence churn. 


**Customer Churn Analysis Report …**

🔎 **Exploratory Data Analysis (EDA)**
EDA was conducted to identify trends and behavioural patterns associated with churn.

Key insights included:

📉 Customers with lower transaction activity were more likely to churn
⚠️ Unresolved customer service issues correlated with higher churn probability
📱 Lower digital engagement and login frequency were strong churn indicators

These findings helped guide feature selection for the predictive model. 

🧹 **Data Cleaning & Preprocessing**
Several preprocessing steps were applied to ensure the dataset was suitable for machine learning:

- Handling missing values using median and mode imputation
- Detecting and capping outliers
- Standardising numerical variables
- Encoding categorical variables using one-hot encoding
- Converting datetime features into numerical recency indicators

The final dataset was cleaned and structured for model training. 


🤖 **Task 2 – Machine Learning Model Development**

The second phase involved building and evaluating a predictive model to identify customers at risk of churn.

⚙️ **Model Selection**

A Random Forest classifier was selected due to its ability to:

🌳 Handle structured tabular data effectively
🔗 Capture non-linear relationships
📊 Provide interpretable feature importance scores
🛡️ Reduce overfitting through ensemble learning

The model was trained using stratified 5-fold cross-validation to ensure robustness and generalisation. 

📏 **Model Evaluation**

Several evaluation metrics were used to assess model performance:

🎯 Precision
🔍 Recall
⚖️ F1 Score
📈 ROC-AUC
📊 Confusion Matrix

Using multiple metrics ensured the model was evaluated comprehensively, particularly given the imbalance often present in churn datasets. 

🔑 **Feature Importance**

Feature importance analysis identified key factors influencing churn, including:

📱 Customer engagement levels
💳 Transaction behaviour
🛠️ Service interaction outcomes

These insights provide valuable information for developing targeted retention strategies. 


📈 **Business Impact**

The predictive model can support Lloyds Banking Group by:

🚨 Identifying customers likely to churn
🎯 Enabling proactive retention strategies
🤝 Personalising engagement with high-risk customers
📊 Improving long-term customer loyalty and satisfaction

The insights generated from this analysis allow the business to make data-driven decisions that reduce customer attrition.

🛠️ **Tools & Technologies**
💻 **Programming & Libraries**

Python
Pandas
NumPy
Scikit-learn

📊 **Data Analysis**

- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Engineering

🤖 **Machine Learning**

- Random Forest Classifier
- Cross-Validation
- Hyperparameter Tuning

📉 **Visualisation**

- Matplotlib
- Seaborn


🧠 **Key Skills Demonstrated**

- Data Cleaning & Preprocessing
- Exploratory Data Analysis
- Machine Learning & Predictive Modelling
- Model Evaluation & Validation
- Business Insight Communication


🎓 **Key Learnings**

- Customer behaviour data provides strong signals for predicting churn
- Proper data cleaning and feature engineering significantly improve model performance
- Ensemble models, such as Random Forest, are effective for structured classification problems
- Clear interpretation of model outputs is essential for business decision-making
Ensemble models such as Random Forest are effective for structured classification problems

Clear interpretation of model outputs is essential for business decision-making
