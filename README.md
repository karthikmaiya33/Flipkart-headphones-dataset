# Data-Analysis-Flipkart headphones dataset

Flipkart is an Indian e-commerce company, headquartered in Bangalore, Karnataka, India, and incorporated in Singapore as a private limited company. One of the several types of products is headphones. Flipkart facilitates a wide variety of headphone types from different companies.
We are considering the dataset involving the details of headphones having ratings and price summary to analyze the finest headphones.

## Project Synopsis

>> This repo contains Data Cleaning, Exploratory Data Analysis, and Data Visualization of Flipkart headphones dataset taken from the Kaggle website [https://www.kaggle.com/].

-------------------------------
## Project Walk-through

### Data Collection

Flipkart headphones dataset taken from the Kaggle website consisted of 7 attributes and 1000 tuples, the attributes are:
product name, color, type, avg_rating, num_of_ratings, selling_price, MRP

------------------------------


## Data Cleaning

After collecting the data, checked for the null and duplicate values present in the dataset to provide better accuracy of the result by removing it. Changes I made and what all variables & scripts I wrote:

    * Changed title to the Product name.
    * Parsed company name out of Product name. 
   
-------------------------------
## EDA {Exploratory Data Analysis}

* All the imported distributions from the data cleaning data-set, I looked at the distributions of the data and the value counts for the various numerical and categorical variables.
* Using **Matplotlib & Seaborn**, categorized and crafted a beautiful data visualisation charts & plots
* Below are a few highlights from the *Pivot tables, Barplots & HeatMaps*.


![image](https://user-images.githubusercontent.com/98012611/155849423-4234fe97-89af-45eb-a902-e37ebc56c60e.png)

![image](https://user-images.githubusercontent.com/98012611/155849435-9a4c2bf8-7011-4452-8fdd-f50b8671d444.png)

![image](https://user-images.githubusercontent.com/98012611/155849455-c99c2dc8-e2bc-442f-a726-2091d967cb52.png)


-----------------


## Resources Consumed for this project & where you can find them:

    Python Ver: 3.9.0
    Packages Used: Pandas, Numpy, Matplotlib, Seaborn, and Wordckoud.

* Matplotlib Documentation: [Click here](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.boxplot.html?highlight=boxplot#matplotlib.pyplot.boxplot)
* Seaborn Documentation: [Click here](http://seaborn.pydata.org/examples/many_pairwise_correlations.html)

-----------------------------
