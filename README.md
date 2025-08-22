# ML-Game-Recommendation-System
This project aims to enhance the gaming experience by providing personalized game recommendations based on user behavior and preferences on the Steam platform. It leverages unsupervised learning to cluster users into behavioral segments and uses supervised models to predict purchase likelihood.


🧠 Project Overview
We analyze behavioral data from over 20,000 Steam users, including playtime, purchase history, and genre preferences. The system identifies user clusters and predicts game affinity, offering tailored recommendations through an interactive interface.

🛠️ Tools & Technologies
Python, Pandas, NumPy – Data cleaning and manipulation

Matplotlib, Seaborn – Data visualization

Scikit-learn – Clustering (KMeans, DBSCAN), PCA, classification (Logistic Regression, Random Forest)

Gradio – Interactive user interface

Google Colab – Model development and deployment

📊 Workflow
Data Cleaning & Preprocessing

Handling missing values, outliers, and categorical encoding

Feature Engineering

Behavioral metrics: total playtime, purchase ratio, genre affinity

Clustering

KMeans and DBSCAN to segment users

Dimensionality Reduction

PCA for visualization and model efficiency

Classification

Predicting purchase likelihood using supervised models

Interface Deployment

Gradio app to display user profile and game recommendations

📈 Results
Achieved 99% accuracy with Random Forest

Identified 4 distinct user personas

Delivered personalized recommendations via a clean UI

🌟 Highlights
Combines unsupervised and supervised learning

Interactive and scalable design

Ready for integration with other gaming platforms


