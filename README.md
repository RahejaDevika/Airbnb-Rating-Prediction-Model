# Airbnb-Rating-Prediction-Model
This project builds a predictive model to estimate whether an Airbnb listing will earn a perfect five-star rating. Using listing, host, and review data combined with external crime statistics and topic modeling on guest reviews, the analysis uncovers key factors driving guest satisfaction and pricing power.

## Project Overview
By analyzing structured listing metadata, host attributes, review history, and external datasets, this project identifies the variables that most influence guest experience, listing visibility, and host revenue potential. The goal is to help hosts improve performance through data-driven insights.

## Tools & Techniques
* Python, Pandas, NumPy, Scikit-Learn

* Topic Modeling for text feature extraction from guest reviews

* Feature Engineering using structured and unstructured data

* Classification Models for rating prediction

* Data Visualization with Matplotlib and Seaborn

## Results & Insights
* The XGBoost classifier emerged as the best-performing model, achieving a validation accuracy of 78%, a True Positive Rate (TPR) of 48.22%, and a False Positive Rate (FPR) of 10%, demonstrating strong generalization and sensitivity under the project’s constraints.

* The model incorporated 85 optimized features, including both structured and text-derived variables. Key predictors of a perfect rating included host responsiveness, first review timing, instant booking availability, host experience, and cleanliness-related keywords from reviews.

* Listings with lower host experience, fewer fees, and amenities like free parking and washers tended to receive more perfect ratings.

* Text-based topic modeling revealed that words such as “clean,” “comfortable,” “safe,” and “responsive” were strongly associated with high guest satisfaction.

* External data, such as crime incidents by state, meaningfully improved predictive power, showing how local safety perceptions can affect guest reviews.

* These insights provide actionable strategies for Airbnb hosts and managers to enhance listing quality, boost visibility, and improve guest experience through data-driven recommendations.
