# PredictWasteAct – Smart Food Waste Prediction & NGO Matcher
PredictWasteAct is a machine learning-based Streamlit application that aims to reduce food waste in commercial kitchens and events by predicting excess food and recommending suitable NGOs for redistribution. It leverages predictive modeling and location intelligence to enable efficient food donations.

# 🌟 Key Features
Predict Food Surplus: Estimates the number of people who can be served based on event inputs.

Suggest Nearby NGOs: Filters and ranks NGOs based on distance and available capacity.

Visual Comparison: Displays NGO capacities against predicted surplus.

CSV Export: Allows downloading the top NGO suggestions.

# 🧠 Tech Stack
Machine Learning: XGBoost

Web Framework: Streamlit

Geolocation: geopy, geodesic

Data Handling: pandas, numpy

Visualization: matplotlib

# 📦 Datasets Used
1. Food Wastage Prediction Dataset
This dataset was sourced from Kaggle and contains various event-level parameters such as guest count, quantity of food prepared, pricing tiers, and food type. These features are used to train a machine learning model that predicts how many people the leftover food can serve.

[Download Food Wastage Dataset from Kaggle](https://www.kaggle.com/datasets/trevinhannibal/food-wastage-data-in-restaurant?resource=download)


2. NGO Dataset (Hyderabad)
A custom-curated dataset created through primary data collection from NGOs in Hyderabad. It includes NGO names, addresses, strengths (capacity to serve), and contact details. The dataset is used to match predicted food wastage with suitable NGOs based on distance and capacity.

⚠️ Due to privacy and ownership considerations, the NGO dataset is not publicly available.

📬 If you're a student, researcher, or developer interested in academic/nonprofit use, feel free to email me at [pramithabodepudi@gmail.com] to request access.
