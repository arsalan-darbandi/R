
# c. Data Understanding

In previous section we understand what is the problem and what kind of data and result we are looking for. In this section we should check that is the data relevant to the problem? Is it vakud and reflect our expectations and is the data quality, quantity, and recency sufficient to continue the project? 
One fundamental technique in this phase is data visualization. In particular, a few things to look out for are outliers, highly skewed distributions, correlations amoung variables, and explicable values and errors and missing values but there are just some examples and depends on type of problems and data we maybe should use other methods.  

Terminology,
<img align="right" src="https://github.com/asikhalaban/R/blob/master/img/Screen%20Shot%202016-11-05%20at%202.07.07%20PM.png" width="350"><br>
- The information in the rows of the table are called records, instances, observations, or data objects.
- The columns of the table are alternatively referred to as attributes, features or variables.
Normally, number of attributes is less than number of records. However, sometime number of attributes is equal or more than number of records. Therefore in these cases we have difficaulty which 
- The set of possible values for the attribute is called as a Domain. 
<br>

## Outline

###   [I) Data Quality] (#Quality)
###  [II) Data Visualization] (#Visualization)
### [III) Correlations] (#Correlation)
###  [IV) Outliers] (#Outlier)
###   [V) Missing Values] (#Missing)
###  [VI) Dimension Reduction and Principal Component Analysis] (#PCA)

<br><br><br><br>

<a name="Quality"/>
## I) Data Quality

Low data quality makes it impossible to trust analysis results. 
Data quality has three dimensions, Accuracy, Completeness, and Timeliness. 

Accuracy:
Closeness between the recorded and true value. Noicy measurements, limited precision, erroneous measurements, systematic issues,rule changes over time are some sources of inaccuracy. 
There are two types of accuracy, Syntactic and Semantic Accuracy. Syntactic inaccuracy when entry is not in the domain. such as word wrong spelling such as fmale instead of female or negative value for age field. Semantic inaccuracy, when entry is in the domain, but not correct. For instance, John Smith is female. So name or sex is incorrect.
Completeness: 
There are two types of incompleteness, Missing records, and missing attribute values. 
When there are missing values in data, two questions must be asked. Why is the data missing? How is the missing data represented?
Unbalanced data is also considered as another type of completeness. The data set might be biased to one type of records. 
Timeliness:
Is the available data up to date?(Recency) Does the data reflect the current nature of the problem domain?(Obsolescence)


<br><br>

<a name="Visualization"/>
## II) Data Visualization

There are two primary motivations for visualization, Exploring and Explaining.  
When You are exploring, not exactly sure what the data has so by doing visualization you can get a sense of the relationships but when you are explaining, you understand what the data is telling you. 
Also, you are graphs don't have to look perfect and it can be imrecise and noisy. However when you are explaining  you need to make sure that you can pair down information to simplest form. 
At last, exploring should be iterated quickly and experimented on but when you are explaining it has to have short attention spans. 

This is very important that how do we explore? There are three different basic ideas. 
- Univariate analyses: Descriptive statistics, Frequency tables, Histograms and Densities, Box plots
- Bivariate analyses: Correlations and Heatmaps, Scatterplots, Trends, Cross tabulaitons
- Multivariate analyses: Parallel plots, Mosaic plots, Regression, PCA, MDS, Variable clistering

[Read More about these methods for exploring](https://github.com/asikhalaban/R/blob/master/Data-Exploring.md)

<br><br>

<a name="Correlation"/>
## III) Correlations

<br><br>

<a name="Outlier"/>
## IV) Outliers

<br><br>

<a name="Missing"/>
## V) Missing Values

<br><br>

<a name="PCA"/>
## VI) Dimension Reduction and Principal Component Analysis
