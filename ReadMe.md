# A look into vehicle depreciation

I have written a story on Medium for this project which can be viewed [here](https://medium.com/@cristian.capsuna/should-you-care-about-car-depreciation-d2e4d92a58fb)

## Installation

To be able to open and view the files you need Jupyter Notebook.
To run a project like this you would need the following python lybraries:
1. pandas
2. numpy
3. matplotlib
4. seaborn
5. scikit-learn

## Project motivation

I wanted to investigate the validity of some myths regarding car depreciation using real data by posing the following quesitons:  
  
Question 1: Do SUVs depreciate less than saloons/estates?  
Question 2: Does doing less milage reduce depreciation?  
Question 3: Does having a car with a bigger engine reduce depreciation?  
Question 4: Do some brands depreciate less than others?
  
To answer these questions I have created a webscraper and captured ~24,000 data points for the BMW brand and ~5,000 data points for the Jaguar brand.

## Tabel of content

1. Depreciation_analysis a guided notebook showing the entire analysis process and what it yielded with respect to the questions I posed.
3. BMW_ML is where I attempt to build machine learning models that can predict car pricing. I managed to build a regression model and a random forrest model. Bother had an R**2 score of over 90% for the test data set.

## Conclusions

Question 1 conclusion: SUVs do tend to depreciate slightly less than saloons/estates for the brands and car market that I have looked at.  
  
Question 2 conclusion: Doing less mileage can reduce depreciation however the sensitivity to mileage varies from car type to car type and brand to brand.  
  
Question 3 conclusion: I was unable to find any connection between engine size and depreciation  
  
Question 4 conclusion: When comparing BMW to Jaguar I have found that Jaguar does perform slightly better both in terms of depreciation and mileage sensitivity.

## Awknowledgements

I would like to thank the discord scrapy community for helping me iron out some of the issues that came with trying to build a web scraper from scratch. I would also like to thanks the people from StackOverflow from also lending me help when I stumbled on various problems I could not figure out on my own.