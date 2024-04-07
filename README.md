
# Exploratory Data Analysis of Unicorn Companies

This repository contains a Jupyter notebook performing exploratory data analysis on a dataset of unicorn startup companies (valued over $1B).

## Dataset
The dataset is from Kaggle and contains information on over 1000 unicorn companies globally as of 2022. The features include:
- Company name
- Valuation amount
- Industry
- Location (country, state/region)
- Founded year
- Number of funding rounds
- Sector (ICT, Health, Finance etc.)

## The objectives of this EDA are
- Understand distributions of valuation amounts by industry/location
- Identify outliers and trends in valuations over time
- Check for correlations between funding rounds and valuations
- Analyze counts of top industries/locations of unicorns
- Gain insights to find patterns in successful unicorns

## Analysis Steps
The notebook contains the following analysis:
1. Data loading and cleaning
2. Summary statistics of valuations by industry/location
3. Histogram and boxplot of valuations
4. Plot of valuations vs funding rounds
5. Count plots of industries and countries
6. Additional plots/analysis as needed

## Key Findings
Some notable results from the EDA are:
- ICT dominates in number of unicorns (33%) followed by Health (16%)
- US has the most unicorns (45%) while China is rapidly catching up
- Strong positive correlation between funding rounds and valuations
- Highest valued unicorns are in FinTech, E-commerce and SaaS sectors
- Visualization of trends over years shows rapid growth in recent periods

## Requirements
- Python 3.7+
- Libraries: Pandas, NumPy, Matplotlib, Seaborn

## Future Improvements
Areas that could be expanded:
- Modeling relationships between features
- Cluster/grouping analysis based on traits
- Additional visualizations for effective communication
- Deeper analysis of time series trends, such as looking at seasonal patterns
