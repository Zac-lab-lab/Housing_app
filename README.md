# House Price Analysis App

A Streamlit application for analyzing house price data with an intuitive, clean interface inspired by Apple's design principles.

## Features

- CSV file upload and preview
- Interactive price trend visualization
- Location-based price analysis
- Summary statistics
- Clean, minimalist design

## Installation

1. Install the required dependencies:
streamlit
pandas
seaborn
matplotlib
plotly
numpy

##Usage 

1. Start streamlit app by running the following command: streamlit run Housingapp.py

2. Upload a CSV file containing house price data.

The CSV file should have the following columns:
- Date (YYYY-MM-DD format)
- Price (numeric)
- Bedrooms (numeric)
- Bathrooms (numeric)
- SquareMeter (numeric)
- Location (text)

## Sample Data from housing_prices.csv

Date,Price,Bedrooms,Bathrooms,SquareMeter,Location
2024-01-01,500000,3,2,139.35,North Wollongong
2024-02-01,520000,4,2,148.64,South Wollongong
2024-03-01,550000,3,2,144,North Wollongong
2024-04-01,490000,2,1,111.48,South Wollongong
2024-05-01,600000,4,3,167.23,East Wollongong
2024-06-01,530000,3,2,148.64,West Wollongong
2024-07-01,580000,4,3,162.58,North Wollongong
2024-08-01,510000,3,2,144,East Wollongong
2024-09-01,620000,4,3,171.87,South Wollongong
2024-10-01,540000,3,2,153.29,West Wollongong
2024-11-01,590000,4,3,157.93,North Wollongong
2024-12-01,520000,3,2,148.64,East Wollongong
