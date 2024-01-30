# Premier League Match Prediction

This project aims to predict the outcomes of Premier League matches using historical match data and machine learning techniques.

## Overview

The project involves the following steps:

1. **Data Collection**: Scraping Premier League match data and team statistics from [FBref](https://fbref.com/).
2. **Data Processing**: Cleaning and preprocessing the collected data.
3. **Feature Engineering**: Creating relevant features for the prediction model.
4. **Model Training**: Training a Random Forest Classifier to predict match outcomes.
5. **Model Evaluation**: Evaluating the model's performance using precision score.
6. **Rolling Averages**: Incorporating rolling averages of key statistics for better predictions.
7. **Visualization**: Visualizing the predictions and performance metrics.

## Requirements

- Python 3.x
- Libraries: requests, BeautifulSoup, pandas, scikit-learn

## Usage

To follow this project, please install the following locally:

* JupyerLab
* Python 3.8+
* Python packages
    * pandas
    * requests
    * BeautifulSoup
    * scikit-learn
    
## Data

We'll be scraping [FBref](https://fbref.com/en/) to get our data in the first part of this project (`scraping.ipynb`).

## License 

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
