# Zomato Data Analysis

This project performs exploratory data analysis on the Zomato restaurant dataset for Bengaluru, India using R.

## Data

The data is obtained from Kaggle: https://www.kaggle.com/datasets/rajeshrampure/zomato-dataset

It contains information on over 8,000 restaurants including:

- Restaurant name
- Location
- Cuisine style
- Average cost for two people
- Whether delivery/takeaway is available
- Whether table booking is available
- Ratings
- Number of ratings

## Analysis

The R Markdown report `zomato.Rmd` performs the following analyses:

- Data preprocessing and cleaning
- Visualizing delivery availability
- Visualizing table booking availability 
- Finding top 10 restaurants by rating and votes
- Relationship between price and rating
- Top rated restaurant by location

## Prerequisites

The following R packages need to be installed:

- readr
- dplyr
- ggplot2

## Usage

To run the analysis:

1. Download the data and place `zomato.csv` in the working directory 
2. Open `zomato.Rmd` in RStudio
3. Install any missing packages
4. Click Knit to generate the Markdown report

The output is a PDF report summarizing the key findings.

## Results

Key observations from the analysis:

- Many restaurants do not offer online delivery/takeaway
- Very few facilitate online table booking
- Positive correlation between price and rating
- Top rated restaurants by location

The report provides visualizations and actionable insights for Zomato.

## Contributing

Pull requests to extend the analysis are welcome! Some ideas:

- Cluster restaurants by cuisine style 
- Predict rating based on other factors
- Compare neighborhoods
- Interactive maps
