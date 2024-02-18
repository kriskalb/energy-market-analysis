# Futures Contracts Analysis Project
## Overview

### This project focuses on analyzing historical futures contracts data. The dataset was extracted from a database using advanced SQL queries. The main objectives of this project include:

    Determining the range of price differences (spread) between front-month (M+1) and the following month (M+2) contracts and investigating the seasonality of this range.
    Identifying periods when the price difference between M+1 and M+2 contracts was statistically inflated or deflated, providing investment opportunities.
    Generating BUY/SELL signals for individual contracts and/or pairs of contracts (transactions at the same time – calendar spreads).

### The analysis involves utilizing various libraries including pandas, matplotlib, seaborn, xgboost, and prophet, along with SQL for data extraction.
## Project Goals

The primary goals of this project are:

    To conduct in-depth analysis of historical futures contracts data.
    To identify patterns and dependencies between different contract months.
    To develop trading strategies based on the identified patterns and price differentials.

## Main Features

Key components of this project include:

    Data Preprocessing: Comprehensive cleaning and preprocessing of the dataset to ensure quality data for analysis.
    Statistical Analysis: Analyzing price differences between different contract months and identifying statistical anomalies.
    Signal Generation: Generating trading signals (BUY/SELL) based on the analyzed data.
    Visualization: Utilizing matplotlib and seaborn for visualizing data trends and patterns.

## Technologies Used

This project makes use of the following libraries and technologies:

    Python: Primary programming language for data analysis and modeling.
    pandas: Data manipulation and analysis.
    matplotlib and seaborn: Data visualization.
    xgboost: Machine learning for predictive modeling.
    prophet: Time series analysis.
    SQL: Data extraction from the database.

## Installation Instructions

To run this project locally, follow these steps:

    Clone the repository: git clone 'https://github.com/your-username/futures-contracts-analysis'
    Navigate to the project directory: cd futures-contracts-analysis
    Install the required Python packages: pip install -r requirements.txt
    Run the Jupyter Notebook or Python script to perform analysis and generate signals.
    Due to the large size of datasets, download them from [insert dataset source] and place them in the appropriate directory within the project.

It is recommended to run the project in Google Colab for easier access to computational resources.
## Authors

    kriskalb {https://github.com/kriskalb/}

## License

This project is open-source.

Feel free to replace "Your Name" in the Authors section with your name or the names of any collaborators. You can also replace the GitHub repository URL with your project's URL.
