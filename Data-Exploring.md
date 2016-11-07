
# Data Exploring

This page will show that how Data Exploring could be useful for understanding a data. 
This is very important that how do we explore? There are three different basic ideas. 
- Univariate analyses: Descriptive statistics, Frequency tables, Histograms and Densities, Box plots
- Bivariate analyses: Correlations and Heatmaps, Scatterplots, Trends, Cross tabulaitons
- Multivariate analyses: Parallel plots, Mosaic plots, Regression, PCA, MDS, Variable clistering


## Descriptive Statistics:

R provides a wide range of functions for obtaining summary statistics which you can find it [here](http://www.statmethods.net/stats/descriptives.html). 
In the commands below you can find one of the methods for decriptive statistics.
```
library(plyr) # To call package that has baseball dataset
?baseball # Reading more about baseball data
data("baseball") # Calling baseball dataset
summary(baseball) # Calling descriptive statistics function. 

## Result

      id                 year          stint           team                lg           
 Length:21699       Min.   :1871   Min.   :1.000   Length:21699       Length:21699      
 Class :character   1st Qu.:1937   1st Qu.:1.000   Class :character   Class :character  
 Mode  :character   Median :1970   Median :1.000   Mode  :character   Mode  :character  
                    Mean   :1961   Mean   :1.093                                        
                    3rd Qu.:1988   3rd Qu.:1.000                                        
                    Max.   :2007   Max.   :4.000                                        
                                                                                        
       g                ab              r                h               X2b       
 Min.   :  0.00   Min.   :  0.0   Min.   :  0.00   Min.   :  0.00   Min.   : 0.00  
 1st Qu.: 29.00   1st Qu.: 25.0   1st Qu.:  2.00   1st Qu.:  4.00   1st Qu.: 0.00  
 Median : 59.00   Median :131.0   Median : 15.00   Median : 32.00   Median : 5.00  
 Mean   : 72.82   Mean   :225.4   Mean   : 31.78   Mean   : 61.76   Mean   :10.45  
 3rd Qu.:125.00   3rd Qu.:435.0   3rd Qu.: 58.00   3rd Qu.:119.00   3rd Qu.:19.00  
 Max.   :165.00   Max.   :705.0   Max.   :177.00   Max.   :257.00   Max.   :64.00  
                                                                                   
      X3b               hr              rbi               sb                cs      
 Min.   : 0.000   Min.   : 0.000   Min.   :  0.00   Min.   :  0.000   Min.   : 0.0  
 1st Qu.: 0.000   1st Qu.: 0.000   1st Qu.:  1.00   1st Qu.:  0.000   1st Qu.: 0.0  
 Median : 1.000   Median : 1.000   Median : 14.00   Median :  1.000   Median : 0.0  
 Mean   : 2.194   Mean   : 5.234   Mean   : 29.59   Mean   :  5.168   Mean   : 2.1  
 3rd Qu.: 3.000   3rd Qu.: 7.000   3rd Qu.: 51.00   3rd Qu.:  5.000   3rd Qu.: 3.0  
 Max.   :28.000   Max.   :73.000   Max.   :184.00   Max.   :130.000   Max.   :42.0  
                                   NA's   :12       NA's   :250       NA's   :4525  
       bb               so              ibb               hbp               sh        
 Min.   :  0.00   Min.   :  0.00   Min.   :  0.000   Min.   : 0.000   Min.   : 0.000  
 1st Qu.:  1.00   1st Qu.:  4.00   1st Qu.:  0.000   1st Qu.: 0.000   1st Qu.: 0.000  
 Median : 11.00   Median : 19.00   Median :  0.000   Median : 0.000   Median : 1.000  
 Mean   : 22.49   Mean   : 29.26   Mean   :  2.292   Mean   : 1.543   Mean   : 3.388  
 3rd Qu.: 38.00   3rd Qu.: 45.00   3rd Qu.:  3.000   3rd Qu.: 2.000   3rd Qu.: 5.000  
 Max.   :232.00   Max.   :189.00   Max.   :120.000   Max.   :51.000   Max.   :52.000  
                  NA's   :1305     NA's   :7528      NA's   :377      NA's   :960     
       sf              gidp       
 Min.   : 0.000   Min.   : 0.000  
 1st Qu.: 0.000   1st Qu.: 0.000  
 Median : 1.000   Median : 2.000  
 Mean   : 1.842   Mean   : 4.774  
 3rd Qu.: 3.000   3rd Qu.: 8.000  
 Max.   :19.000   Max.   :36.000  
 NA's   :7390     NA's   :5272    
```

## Frequency tables

?????

## Histograms and Densities
