
# Pratilipi Recommendation System

## Overview
This project implements a recommendation system for Pratilipi stories using collaborative filtering (SVD) and content-based filtering. The hybrid model combines both approaches to generate personalized recommendations for users.

## Features
- Collaborative Filtering using Singular Value Decomposition (SVD)
- Content-Based Filtering using cosine similarity of story metadata
- Hybrid Recommendation combining both techniques

## Installation
Ensure you have Python installed, then install dependencies using:
```sh
pip install pandas numpy matplotlib seaborn surprise scikit-learn scipy
```

## How to Run
1. Place `user_interaction.csv` and `metadata.csv` in the project directory.
2. Run the Python script:
```sh
python pratilipi_recommendation.py
```
3. The output will display recommended pratilipis for a sample user.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- surprise
- scikit-learn
- scipy

## File Structure
- `pratilipi_recommendation.py`: Main script implementing the recommendation system
- `user_interaction.csv`: Contains user reading behavior
- `metadata.csv`: Contains metadata about pratilipis
- `README.md`: This file

## Expected Output
A list of recommended Pratilipis for a given user will be printed as output.

## Contact
For any queries, reach out to the project author.

