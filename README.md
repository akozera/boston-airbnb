# boston-airbnb

The repository must have a README.md file that communicates the libraries used, the motivation for the project, the files in the repository with a small description of each, a summary of the results of the analysis, and necessary acknowledgements.

This is a repo that contains my analysis of the Boston AirBnB data from the time period Sep 2016 - Sep 2017. The primary goal of the analysis is to try finding answers to the following business questions:
1. How do reviews influence the price?
2. What areas are the most and least attractive?
3. What are the (surprising) factors influencing the price?

The findings are:
1. The only reviews that matter when it comes to the price are related to the cleanliness and location.
2. Location proved to be important also when considering neighbourhood data — average prices between different areas do vary significantly with least attractive ones being  Dorchester, Mattapan or East Boston and most attarctive - Back Bay, South Boston Waterfront and Fenway.
3. Other factors related to the higher prices are strict cancellation policies and guest verification requirements. Surprisingly (or not for some), higher number of reviews tend to be associated with listings with lower prices.

Details of the analysis can be found in the notebook airbnb.ipynb.

Libraries used in the project are: pandas, numpy, matplotlib, seaborn and sklearn.

Data comes from kaggle.com and can be found here: https://www.kaggle.com/airbnb/boston

