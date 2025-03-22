# UdaRecommendationsWithIBM
For this project you will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like. 

This project is an academic study with Udacity on creating article recommendations.

## Requirements & Packages

- **Python 3**
- **Required Packages:**
  - pandas
  - numpy
  - matplotlib

# Recommendations with IBM

This repository contains a project developed as part of an academic study for Udacity. The goal of this project is to build and evaluate a recommendation system for articles on the IBM Watson Studio platform using various approaches including exploratory data analysis, rank-based recommendations, user-user collaborative filtering, and matrix factorization.

## Overview

The project leverages a dataset containing user-article interactions and article metadata from the IBM Watson Studio platform. By applying several recommendation strategies, the study aims to personalize user experiences and improve how users find relevant articles. The project is divided into several parts:

- **Exploratory Data Analysis:** Understand the data, compute basic statistics, and prepare the dataset.
- **Rank-Based Recommendations:** Recommend popular articles based on interaction counts.
- **User-User Collaborative Filtering:** Recommend articles based on similar user behaviors.
- **Matrix Factorization:** Use Singular Value Decomposition (SVD) to extract latent features and predict user-item interactions.
- **Content-Based Recommendations:** Explore recommendations based on article content.

## Project Structure

- **Recommendations_with_IBM.ipynb:** The main Jupyter Notebook that contains all code for data analysis, recommendation system development, and evaluation.
- **data/**
  - **user-item-interactions.csv:** Dataset containing interactions between users and articles.
  - **articles_community.csv:** Dataset containing article metadata.
- **user_item_matrix.p:** A pickle file storing the user-item matrix for use in matrix factorization.

## How to Run

2. **Open the Notebook:**
   - Launch Jupyter Notebook or JupyterLab and open `Recommendations_with_IBM.ipynb`.

3. **Run the Notebook**
   - Run each cell in the notebook

4. **Review Results:**
   - Results and test outputs are stored within the notebook. 


## Academic Purpose

This project was developed as part of an academic study for Udacity. It demonstrates how to apply common recommendation system techniques and evaluate them using both offline metrics and considerations for real-world user impact. The project emphasizes simplicity and clarity for newcomers to recommendation systems while offering insight into more advanced techniques.

## License

This project is provided for educational purposes as part of an academic study for Udacity.
