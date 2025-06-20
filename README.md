# IBM-Data-Science-Capstone

🚀 Applied Data Science Capstone: Falcon 9 First Stage Landing Prediction

📌 Overview
This project tackles a key challenge in modern space economics: 
predicting whether SpaceX’s Falcon 9 first stage will land successfully. SpaceX has disrupted the aerospace industry by slashing launch costs—charging $62 million per launch compared to competitors’ $165 million+—thanks largely to reusable rockets. By analyzing historical launch data, this project provides actionable insights for companies competing with SpaceX, helping them estimate launch expenses more accurately.

🎯 Objectives
The project is structured into modular workflows, combining data science, machine learning, and interactive analytics to deliver a robust predictive model. Key phases include:

1. Data Collection & Wrangling
Retrieved SpaceX launch records via SpaceX API and performed data cleaning.

Scraped additional Falcon 9 launch data from Wikipedia using BeautifulSoup.

2. Exploratory Data Analysis (EDA) & Feature Engineering
Visualized trends with Matplotlib/Seaborn and engineered features for model improvement.

Mapped launch outcomes geographically using Folium for spatial insights.

3. Database Integration & SQL Analysis
Stored data in IBM Db2 and executed SQL queries for deeper analysis.

4. Interactive Dashboard with Plotly Dash
Built a dynamic Dash app with dropdowns, sliders, and real-time visualizations (pie charts, scatter plots).

5. Machine Learning & Model Tuning
Trained and evaluated models (Decision Trees, SVM, Logistic Regression, KNN) using GridSearchCV.

Best Model: Decision Tree Classifier (94.4% test accuracy).

🔍 Results
Model	Test Accuracy
Decision Tree	0.9444
SVM / K-Nearest Neighbors	0.8333
The Decision Tree outperformed other models, offering reliable predictions for first-stage landing success.

🌟 Explore the Project

Whether you're a data scientist, space enthusiast, or industry professional, this repository offers:

✅ End-to-end predictive modeling

✅ Interactive dashboards

✅ Geospatial and SQL-based analysis

Dive into the notebooks and scripts to see how data science drives innovation in aerospace!


