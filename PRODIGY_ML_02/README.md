Prodigy_ML_02
Customer Segmentation Using K-Means Clustering
Overview

This project implements a K-Means clustering algorithm to group customers of a retail store based on their purchase behavior.

The clustering is performed using the Mall Customers Dataset from Kaggle, which includes customer details such as:

Annual income

Spending score

The goal is to segment customers into meaningful groups that can help businesses understand customer behavior and design targeted marketing strategies.

Problem Statement

To divide customers into different clusters based on their Annual Income and Spending Score using unsupervised machine learning (K-Means clustering).

Algorithm Used

K-Means Clustering

Elbow Method to determine the optimal number of clusters

Requirements
Python Version

Python 3.x

Libraries Required

pandas

numpy

matplotlib

scikit-learn

Installation / Implementation
Option 1: Local Machine

Install the required libraries using:

pip install -r requirements.txt

Option 2: Google Colab

You can run the project directly on Google Colab without installing any libraries locally.

Dataset

Register or log in to Kaggle

Download the dataset Mall_Customers.csv from the following link:
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

Place the downloaded file in the project directory

Features Used for Clustering

Annual Income (k$)

Spending Score (1–100)

Usage

Run the Jupyter Notebook:

Customer_Segmentation_KMeans.ipynb


(or open it directly in Google Colab)

Steps Performed in the Notebook

Load and explore the dataset

Select relevant features for clustering

Apply feature scaling

Use the Elbow Method to determine the optimal number of clusters

Train the K-Means clustering model

Assign cluster labels to customers

Visualize customer segments using scatter plots

Output / Results

Customers are grouped into 5 distinct clusters

Each cluster represents a different type of customer behavior such as:

High income – high spending

High income – low spending

Low income – high spending

Low income – low spending

Average income – average spending

File Descriptions

Customer_Segmentation_KMeans.ipynb
Jupyter Notebook / Google Colab file containing the complete K-Means clustering implementation

Mall_Customers.csv
Dataset used for customer segmentation

README.md
Project documentation including overview, setup instructions, usage details, and file descriptions

Conclusion

K-Means clustering effectively segments retail customers based on their purchasing behavior. These insights can help businesses in customer targeting, personalized marketing, and improving customer satisfaction.
