# RFM Customer Value using Python Pandas
### Recency Frequency And Monetary (RFM)
RFM is a scoring system commonly used as a means to calculate a customer's value in almost any business.
In this example, by using Python3 Pandas library, we can easily calculate and rank customers by tiering them

__*Step by Step instructions are within the ipython notebook code*__
	
## The Data
### sampleData.csv / 122 rows 31 Columns
The csv file contains randomised Id, date fields, emails from random generators.
This is simulated to be an online store, selling various products categories
1. Name - (random generated)
2. userId - internally used identification of customers (random generated)
3. gender -(male,female,unknown)
4. Creation date time stamp
5. Account age (Days *outdated)
6. last seen timestamp
7. last seen days ago (Days *outdated)
8. Posted orders
9. Completed orders
10.Transaction Scoring
11. Recency in days (since last Transacted)
12. Indecisive scoring 
  * Can be collected in many different ways
  * Add to cart/ remove from cart, time spent on certain products page etc.
  * Based on pre-defined metrics 0-1.0 scoring, 1 means very indecisive
13. Email - (random generated)

## Library used
### Python3
1. pandas
2. numpy
3. matplotlib.pyplot
4. seaborn
5. random

## Built With
* [Python](https://www.python.org/download/releases/3.0/) - Language
** Python libraries
* [Pandas](https://pandas.pydata.org/) - Python pandas library
* [Seaborn](https://seaborn.pydata.org/) - Python data visualization library

## Authors

* Zenger Soong Cun Yuan

## Acknowledgments
** Data Mocking
* [mockaroo.com](https://www.mockaroo.com/) - Realistic Data Generator
* [name-generator](https://www.name-generator.org.uk/quick/) - Simple Name generator


