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
NGO Dataset: A custom-curated dataset of NGOs in Hyderabad, including name, address, strength, and contact details.

[Download Food Wastage Dataset from Kaggle](https://www.kaggle.com/datasets/trevinhannibal/food-wastage-data-in-restaurant?resource=download)


Input Features: Simulated event-level features like guest count, food quantity, pricing indicators, and food type used to predict wastage.

💡 Due to privacy and ownership considerations, the NGO dataset is not publicly hosted.

📬 If you're a student, researcher, or developer interested in accessing the dataset for academic or nonprofit purposes, feel free to reach out to me at [your.email@example.com].
