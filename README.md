# Data Science Portfolio

| Portfolio Information | Description |
| --- | --- |
| Portfolio #1 | E-commerce Product Cross - Price Elasticity |
|Language| Python|
|Libraries Used| sklearn, NLTK, Numpy, Pandas, re(Regex), matplotlib, seaborn, wordcloud|
|Projects Count| 4|
| Author | Ileana Cabada |
| Dataset | [Electronic_Pricedataset](https://www.kaggle.com/datafiniti/electronic-products-prices)|


**About Portfolio** - This portfolio's main purpose is to analyze price tendencies and impact in demand by pricing variation through time in various e-commerce platforms for brands among similar electronic products.

Hypotheses
i.e. Does product impression demand of company X  increase,if direct company competitor Y increases their prices on the same or similar electronic products within a certain timeframe?
Does free shipping boost impressions in electronic products? If yes, which products tend to have better results? 


**About the dataset** - 
Original dataset includes only electronic products with following features:
product name, product description, product advertisment dateseen (impression), discount price, regular price, merchant (e-commerce website) and others

# Content 
## Part 1 .- Data Cleaning and Preprocessing ##


 - ### 1.1.- [E-commerce Product Data Cleaning](https://github.com/ileanadatamania/Data-Science-Portfolio/blob/master/DataCleaning_price.ipynb) 
 managing null values, dropping of unused features, text normalization 

#### Libraries 
- **RE(Regex), Matplotlib, Pandas and Numpy**  


- ### 1.2.- [Unsupervised Text Classification with TDIF Vectorizing and Kmeans](https://github.com/ileanadatamania/Data-Science-Portfolio/blob/master/Kmeans_TDIF_NLP_TextClustering.ipynb)
#### About Model Implemented
Due to the fact that the dataset doesn't count with category labelling for further price analysis between similar products (**i.e. tablets, headphones**).

**Unsupervised texting clusterinng model** was implemented by using texting preprocessing techniques such as Lemmatization, Regex, Tokenization, followed by TF-IDF Vectorization and Kmeans algorithm.

Category_name and Cluster features were created from unique product names with their respective product description.  

#### Libraries 

- **NLTK, sklearn, RE(Regex), WordCloud, Matplotlib, Pandas and Numpy**  


WordCloud       |  Electronic Category Label Clusters
:-------------------------:|:-------------------------:
![](https://github.com/ileanadatamania/images1/blob/master/wordcloud.png)  |  ![](https://github.com/ileanadatamania/images1/blob/master/clustword.png)

## Part 2 .- Exploratory Data Analysis
 
- ### 2.1.-[Price Exploratory Data Analysis](https://github.com/ileanadatamania/Data-Science-Portfolio/blob/master/EDA_Price.ipynb)

For further calculation of price elasticities with multilinear regression model. This price exploratory analysis was executed for following reasons:

- Product Condition Selection
- Price Distribution Analysis
- Discount Price Correlation with Impression Total Count per Category
- Merchant (e-commerce) Impression Time Analysis

#### Libraries 

- **seaborn, Matplotlib, Pandas and Numpy**  

Price Distribution Plot     | Price Discount Correlation Heatmap
:-------------------------:|:-------------------------:
![](https://github.com/ileanadatamania/images1/blob/master/distplot.png)  |  ![](https://github.com/ileanadatamania/images1/blob/master/heatmapdisc.png)

## Part 3 .-  Price Elasticity and Cross-Price Elasticity of Demand ##

- ### 3.1 [Price Elasticity of Demand](https://github.com/ileanadatamania/Data-Science-Portfolio/blob/master/Price_Elasticityof_Demand.ipynb)
In following analysis, we would select Best Buy products as our main price elasticity analysis. For future reference,this model can be implemented in every kind of vendors by e-commerce or brick and mortar.

 **Hypothesis Proposed**

 From Bestbuy laptop sample data in 2017. Is impression demand sensitive to its own product price changes? If yes, by how much   impression demand is sensitive to price change?
 
 **Machine Learning Model**

- Linear Regression

Laptop, Desktop Price Elasticity     |
:-------------------------:|
![](https://github.com/ileanadatamania/images1/blob/master/price_elasticity.png)|

- ### 3.2 Cross- Price Elasticity

**To be continued**

   
| Contact Source | Information |
| --- | --- |
| e-mail| ileana.cabada@gmail.com |
| Linkedin | [https://www.linkedin.com/in/ileana-c-24666159/](https://www.linkedin.com/in/ileana-c-24666159/) |
