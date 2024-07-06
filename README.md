# Football Team, Match and Player Analysis

This repository contains the analysis and prediction of football team statistics and player goal spans using various machine learning techniques. The project is divided into several sections, each focusing on different aspects of the analysis.

## Sections

### Section A: Data Exploration
In this section, we explore the provided football match data to understand its structure, check for missing values, and visualize key statistics.
* results.csv: Contains the primary data of the dataset, including details of each match
such as the date, home team, away team, home score, away score, tournament, city,
country, and whether the match was played on neutral ground.
* shootouts.csv: Provides information about matches that were decided by penalty
shootouts, detailing the teams involved and the outcome of the shootout.
* goalscores.csv: Contains the scores of the goals in international games along with
minutes of said goals

### Section B: Data Engineering
Here, we preprocess the data by handling missing values, adding new features, encoding categorical variables, and scaling numerical features to prepare the data for machine learning models.

### Section C: Predicting Match Outcomes
In this section, we utilize different machine learning classifiers to predict whether the home team won the match or not. The classifiers include:
- Support Vector Machines (SVM)
- K-Nearest Neighbors (KNN)
- Decision Trees
- Random Forests
- Bagging
- AdaBoost

### Section D: Clustering the Teams
This section focuses on clustering the national football teams based on their statistics. We first perform data engineering to create a dataset of all the national teams. The clustering algorithms used include:
- K-means Clustering
- Agglomerative Clustering

### Section E: Clustering with and without PCA
Here, we compare the clustering results before and after applying Principal Component Analysis (PCA). PCA helps in reducing the dimensionality of the data, making the clusters more distinct and interpretable. The clustering algorithms used are:
- K-means Clustering
- Agglomerative Clustering

### Section F: Predicting Player Goal Spans
In this section, we focus on the goal spans of players. We engineer a dataset from the `goalscorer.csv` file to determine if we can predict whether a player's goal span (the duration between their first and last goals) will be more than one year or not. We use the Random Forest classifier for this prediction.

## Files

- `ML_HW2_207933672_208642868.ipynb`: The Jupyter notebook containing the full analysis, code, and visualizations.
- `Assignment 2.pdf`: The assignment brief outlining the tasks and objectives.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required libraries: numpy, pandas, matplotlib, seaborn, scikit-learn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Football-Team-and-Player-Analysis.git
   ```

2. Navigate to the repository directory:
   ```bash
   cd Football-Team-and-Player-Analysis
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter notebook:
   ```bash
   jupyter notebook ML_HW2_207933672_208642868.ipynb
   ```

## Usage

Follow the steps in the Jupyter notebook to reproduce the analysis and visualizations. The notebook is organized into sections corresponding to the tasks outlined in the assignment.
