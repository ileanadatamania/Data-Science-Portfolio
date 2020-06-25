# Data Science Portfolio

| Portfolio Information | Description |
| --- | --- |
|Language| Python|
|Libraries Used| sklearn, NLTK,statsmodels, Numpy, Pandas, re(Regex), matplotlib, seaborn, wordcloud|
|Projects Count| 6|
| Author | Ileana Cabada |
| Dataset | [Electronic_Pricedataset](https://www.kaggle.com/datafiniti/electronic-products-prices),[AB Testing dataset](https://www.datacamp.com/projects/184)|



**About Portfolio** -Product Price and Cross- Price Elasticities in Advertisment demand, Product Category Labelling, A/B Player Retention Testing, Poisson Distribution, Price Exploratory Analysis

# Content 
# Probability and Statistics #

- ### [Price Elasticity of Ad Impression Demand](https://github.com/ileanadatamania/Data-Science-Portfolio/blob/master/Price_Elasticityof_Demand.ipynb)
In following analysis, we would select Best Buy products as main data sample for our price elasticity analysis. For future reference,this model can be implemented in every kind of vendors by e-commerce or brick and mortar by measuring sales demand

 **Hypothesis Proposed**

From Bestbuy laptop sample data in 2017. Is ad impression demand sensitive to its own product price changes? If yes, by how much ad impression demand is sensitive to price change?
 
#### Statistical Model

- Linear Regression

 #### Libraries
 
- **statsmodels, NumPy, Pandas, Matplotlib**

Laptop, Desktop Price Elasticity     |
:-------------------------:|
![](https://github.com/ileanadatamania/images1/blob/master/PE.png)


- ### [Cross-Price Elasticity of Ad Impression Demand](https://github.com/ileanadatamania/Data-Science-Portfolio/blob/master/Cross-Price_ONLY.ipynb)

 **Hypothesis Proposed**

 How much is ad impression demand influenced by main competitors when they change their prices?
 This model help us to know the naturality of competition between prices of our own price product advertised against main     competitors price product changes

#### Statistical Model

- Multi Linear Regression

 #### Libraries
 
- **statsmodels, NumPy, Pandas, Matplotlib**

Cross-Price Elasticity of 12 Mac Book     |
:-------------------------:|
![](https://github.com/ileanadatamania/images1/blob/master/CPE1.png)


- ### [A/B Retention Testing](https://github.com/ileanadatamania/Data-Science-Portfolio/blob/master/ABtesting_gamedesign.ipynb)


#### Statistical Model

- Poisson Distribution, Bootstrap Distribution

 #### Libraries
 
- **statsmodels, NumPy, Pandas, Matplotlib**


A/B Testing Distribution  |  Poisson Distribution
:-------------------------:|:-------------------------:
![](https://github.com/ileanadatamania/images1/blob/master/AB.png)  |  ![](https://github.com/ileanadatamania/images1/blob/master/Poisson.png)


# Machine Learning and Natural Language Processing #

- ### [Unsupervised Text Classification with TDIF Vectorizing and Kmeans](https://github.com/ileanadatamania/Data-Science-Portfolio/blob/master/Kmeans_TDIF_NLP_TextClustering.ipynb)
#### About Model Implemented
Due to the fact that the dataset doesn't count with category labelling for further price analysis between similar products (**i.e. tablets, headphones**).

**Unsupervised texting clustering model** for the creation of product category label segmentation was implemented by using texting preprocessing techniques such as Lemmatization, Regex, Tokenization, followed by TF-IDF Vectorization and Kmeans algorithm.

Category_name and Cluster features were created from unique product names with their respective product description. 

#### Machine Learning Model

- Kmeans

#### Libraries 

- **NLTK, sklearn, RE(Regex), WordCloud, Matplotlib, Pandas and Numpy**  


WordCloud       |  Electronic Category Label Clusters
:-------------------------:|:-------------------------:
![](https://github.com/ileanadatamania/images1/blob/master/wordcloud.png)  |  ![](https://github.com/ileanadatamania/images1/blob/master/clustword.png)

# Exploratory Data Analysis EDA #
 
- ### [Price Exploratory Data Analysis](https://github.com/ileanadatamania/Data-Science-Portfolio/blob/master/EDA_Price.ipynb)

For further calculation of price elasticities with multilinear regression model. This price exploratory analysis was executed for following reasons:

- Product Condition Selection
- Price Outlier Detection
- Price Distribution Analysis
- Discount Price Correlation with Impression Total Count per Category
- Merchant (e-commerce) Impression Time Analysis

#### Libraries 

- **seaborn, Matplotlib, Pandas and Numpy**  

Price Distribution Plot     | Price Discount Correlation Heatmap
:-------------------------:|:-------------------------:
![](https://github.com/ileanadatamania/images1/blob/master/distplot.png)  |  ![](https://github.com/ileanadatamania/images1/blob/master/heatmapdisc.png)


# Data Cleaning and Preprocessing #


 - ### [E-commerce Product Data Cleaning](https://github.com/ileanadatamania/Data-Science-Portfolio/blob/master/DataCleaning_price.ipynb) 
 managing null values, dropping of unused features, text normalization 

#### Libraries 
- **RE(Regex), Matplotlib, Pandas and Numpy**  

Null, Unique and Datatype column values table    |
:-------------------------:|
![](https://github.com/ileanadatamania/images1/blob/master/Null.png)

   
| Contact Source | Information |
| --- | --- |
| e-mail| ileana.cabada@gmail.com |
| Linkedin | [https://www.linkedin.com/in/ileana-c-24666159/](https://www.linkedin.com/in/ileana-c-24666159/) |
