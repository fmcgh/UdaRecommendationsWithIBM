# UdaRecommendationsWithIBM
For this project you will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like. 

This project is an academic study with Udacity on creating article recommendations.

## Overview

The project leverages a dataset containing user-article interactions and article metadata from the IBM Watson Studio platform. By applying several recommendation strategies, the study aims to personalize user experiences and improve how users find relevant articles. The project is divided into several parts:

- **Exploratory Data Analysis:**  
  Understand the data, compute basic statistics, and prepare the dataset.

- **Rank-Based Recommendations:**  
  Recommend popular articles based on interaction counts.

- **User-User Collaborative Filtering:**  
  Recommend articles based on similar user behavior.

- **Matrix Factorization:**  
  Use Singular Value Decomposition (SVD) to extract latent features and predict user-item interactions.

- **Content-Based Recommendations:**  
  Explore recommendations based on article content.

## Data Set Details

- **user-item-interactions.csv:**  
  Contains interactions between users and articles, including multiple interactions by the same user.

- **articles_community.csv:**  
  Contains metadata for articles on the IBM Watson Studio platform, including fields like article ID, title, and content descriptors.

- **user_item_matrix.p:**  
  A pickle file storing the preprocessed user-item matrix for use in matrix factorization.

## Project Results

The project produces several outputs:
- **Exploratory Analysis:**  
  Computes key statistics such as the median and maximum interactions per user, unique article counts, and identifies the most viewed article.

- **Recommendation Lists:**  
  Implements rank-based, collaborative filtering, and matrix factorization methods to generate lists of recommended article IDs and names.

- **Evaluation Metrics:**  
  Uses both offline tests (via the provided `project_tests.py`) and discussions on metrics like prediction error and user engagement (e.g., click-through rates) to assess recommendation performance.

## Requirements & Packages

- **Python 3**
- **Required Packages:**
  - pandas
  - numpy
  - matplotlib

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
