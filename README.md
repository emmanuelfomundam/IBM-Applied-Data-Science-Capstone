🚀 Applied Data Science Capstone

This project is the final capstone for the IBM Data Science Professional Certificate Specialization. It brings together all the concepts, tools, and methodologies learned throughout the specialization into one applied project.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📄 Project Background

SpaceX has revolutionized the commercial space industry by making space travel significantly more affordable. A key factor in this cost reduction is the reusability of the Falcon 9 rocket’s first stage.

- SpaceX advertises Falcon 9 launches at $62M per launch.
- Competitors charge upward of $165M for similar services.
- Much of the cost savings comes from reusing the first stage of the rocket.

Objective:
If we can predict whether the first stage will successfully land and be reused, we can better estimate the cost of a launch. Using publicly available information and machine learning models, this project aims to build such predictions.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📄 Research Questions

- How do variables such as payload mass, launch site, number of flights, and orbit affect the success of the first stage landing?

- Has the rate of successful landings increased over the years?

- What is the best machine learning algorithm for predicting first stage landing success (binary classification)?
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📄 Methodology
1. Data Collection
   Retrieved data from the SpaceX REST API.
   Conducted web scraping from Wikipedia for additional information.
   
2. Data Wrangling
  Filtered and cleaned raw datasets.
  Handled missing values.
  Applied One-Hot Encoding to prepare categorical variables for classification models.

3. Exploratory Data Analysis (EDA)
  Conducted statistical analysis and visualizations.
  Used SQL queries to explore datasets.

4. Interactive Visual Analytics
  Developed geospatial visualizations using Folium.
  Created interactive dashboards with Plotly Dash.

5. Predictive Modeling
  Built multiple classification models (Logistic Regression, Decision Trees, SVM, KNN, etc.).
  Performed hyperparameter tuning to improve performance.
  Evaluated models using appropriate metrics (accuracy, F1-score, confusion matrix).
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📊 Tools & Technologies

- Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
- SQL
- Folium (geospatial analysis)
- Plotly Dash (interactive dashboarding)
- Web Scraping (BeautifulSoup, Requests)
- REST APIs
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
✅ Key Outcomes

- Identified key factors that influence Falcon 9 first stage landing success.
- Analyzed historical landing trends to determine improvements over time.
- Built and compared machine learning models to predict landing outcomes.
- Delivered insights through visualizations and an interactive dashboard.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🚀 Conclusion

This project showcases the end-to-end data science workflow—from data collection to model deployment—applied to a real-world case study: predicting SpaceX Falcon 9 first stage reusability. By combining data engineering, analytics, visualization, and machine learning, we can better understand the cost-saving mechanisms that make SpaceX the leader in the space industry.
