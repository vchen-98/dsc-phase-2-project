# Phase 2 Project

## Business Understanding

Our client is Genesis Capital, a house flipping company, and they are wanting to get in the martel in king county. Being that they are not from king county they need some help to understand the market. They want to know out of all the feathers for the house in king county which features have the most significant effect on the price of a house.They also want to know which feathers affect the house’s price the most, both positively and negatively.

### Business Problem

Business Questions:

What features affect the price significantly?
How do they affect the price, positive and negative ?


## Data Understanding

Interpretation:
This data set is a record of house sales in King County, Washington, between 2014 and 2015. It includes information like the number of bedrooms, square footage (important!), condition, the year it was built, the year it was renovated (if applicable), and the zipcode and latitude/longitude. From this data, we can extrapolate location, age of the house, and size of the house, giving us a good look at how these factors affect the price.

Target: Price

Available Predictors: bedrooms, bathrooms, square footage of living space, square footage of the lot, numuber of floors, waterfront house or not, number of viewers, condition based on a numeric scale, grade based on a numeric scale, square footage of the basement, year the house was built, year the house was renovated, zipcode, latitude/longitude, and square footage of living space of the nearest 15 neighbors

## Data Preparation

Dataset: Entries of sales in King County contains over 21,597 entries form 2014 and 2015 with 21 different features including are target price. Some available predictors are: square footage of living space, number of floors, waterfront house or not and several others.

## Modeling

### First Simple Model



Square Foot Living was chosen for the First Simple Model do to its high correlation with housing price. Be examines the relationship between these two we get an accuracy in are model of 49.3%. For each sqft the price increases by $280 for this model.

### Features

Overall we found that sqft living and lot, number of bedrooms, number of floors, waterfront view, the year the house was built, and it's zip code location has the most significant impact on the price of a house. With our final model set and dont we can see how these features affect the price of a house, namly which top one affects positively/negatively. Having a house with a waterfront alone immediately increases a house by $8.6 hundred thousand. While each bedroom decreases the overall price of a house by $3,800. Our final model has an improved accuracy of 78%.

## Conclusion




