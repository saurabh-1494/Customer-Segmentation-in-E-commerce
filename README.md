# Customer-Segmentation-in-E-commerce
Overview

This project performs customer segmentation using clustering techniques based on purchasing habits and browsing behavior from an e-commerce dataset. The goal is to identify meaningful customer clusters to support business decisions such as targeted marketing and personalized experiences.

Project Structure

customer_segmentation_report.md: Full report including methodology, code, visualizations, and interpretation

9. Customer Segmentation in E-commerce.csv: Dataset file

Steps Involved

1. Data Preprocessing

Load CSV dataset using pandas

Drop irrelevant or non-numeric features

Handle missing values

Standardize features using StandardScaler

2. Clustering with K-Means

Use Elbow Method to find the optimal number of clusters (k)

Fit K-Means model

Assign cluster labels to the dataset

3. Visualization & Analysis

Visualize clusters using Seaborn pairplot

Print cluster centroids to interpret customer behavior

Installation

pip install pandas scikit-learn matplotlib seaborn

Usage

Run the Python script provided in the report:

python customer_segmentation.py

Make sure the dataset CSV is in the same directory or update the file path accordingly in the script.

Example Output

Elbow Plot to determine optimal clusters

Pair Plot for cluster visualization

Cluster Centers showing average behavior of each group

References

Scikit-learn Documentation

Seaborn Documentation

Dataset provided by the user

Credits

Created with the help of ChatGPT by OpenAI

License

This project is for educational and non-commercial use.

