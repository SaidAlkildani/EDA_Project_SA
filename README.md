
# Exploratory Data Analysis - Said Alkildani

This project aims to explore dataset of house sales in King County. My stakeholder is a buyer with a budget, 5 kids. They wish for a waterfront and an isolated neighborhood with less kids. 

Three hypotheses were formed. Data was cleaned and analyzed to test these hypotheses. 

There are three main notebooks in this repository:

- data fetching notebook
- data cleaning notebook
- data analysis notebook

## Requirements

- pyenv
- python==3.11.3

## Setup

A requirements text file is included to replicate the vitrual environment used for this project.

## Key questions
- Is there a seasonal pattern in house sales of properties with waterfronts?
- Are houses with multiple floors more affordable than single-story houses?
- Assuming number of bedrooms reflects number of kids. Do central houses have less kids? 

## Column Names and descriptions for King County Data Set

- **id** - unique identified for a house
- **dateDate** - house was sold
- **pricePrice** - is prediction target
- **bedroomsNumber** - # of bedrooms
- **bathroomsNumber** - # of bathrooms
- **sqft_livingsquare** - footage of the home
- **sqft_lotsquare** - footage of the lot
- **floorsTotal** - floors (levels) in house
- **waterfront** - House which has a view to a waterfront
- **view** - quality of view
- **condition** - How good the condition is ( Overall )
- **grade** - overall grade given to the housing unit, based on King County grading system
- **sqft_above** - square footage of house apart from basement
- **sqft_basement** - square footage of the basement
- **yr_built** - Built Year
- **yr_renovated** - Year when house was renovated
- **zipcode** - zip
- **lat** - Latitude coordinate
- **long** - Longitude coordinate
- **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
- **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors
- **price_per_sqft** - The price of a square foot for each house, price is divided by lot+living spaces
- **month** - month the house was sold
- **season** - 1-3: winter, 4-6: spring, 7-9: summer, 10-12: fall
- **neighborhood** - neighborhood number assigned to each zip code
- **state** - like_new: old but renovated, old: older than 2010, new: built after 2010
