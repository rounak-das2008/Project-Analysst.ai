# Project-Analysst.ai

## Description
In this project, different Bags' details are scraped from Amazon.in and stored to AmazonProductData.csv file. The details of the product(bags) contains :
* Name of the product
* Product URL
* Product Price
* Ratings
* Number of Reviews
* Review Body
* Description of Product
* Amazon Standard Identification Number (ASIN)
* Product Details(others)
* Manufacturer

Its fetches around 200 products from the search list of multiple pages and store the above product details in the csv file.

The Extract_reviews jupyter file extracts the review informations from the collected data and use it to analyse the sentences filtering out Part of Speech and removing unwanted information.
This project uses TextBlob to analyse the polarity of the reviews if they are positive, negative or neutral.
