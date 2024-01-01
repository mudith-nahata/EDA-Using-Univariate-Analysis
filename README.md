# Exploratory Data Analysis
-->Exploratory data analysis is nothing but delivering the Independent Analysis for both In and Out for the Input data.

-->To Analysis the data in three ways

      1) Univariate Analysis

      2) Bi-variate Analysis

      3) Multivariate Analysis

# Univariate Analysis
--> In the term itself we gonna get an breif idea that it is derived from the two words.

                             * Uni- Means Single
                             
                             * Variate- Means Variable

--> Univariate analysis means doing the independent analysis on the Single column is called as **Univariate Analysis**.

--> So Whenever we are going to do Univariate Analysis We need to also know about the data.

--> Data is classified into two Categories 

      > Numerical data

      > Categorical data

 --> So whenerver we are going to analysis on the data we will undergo with this categories.


# Univariate Analysis on Categorical data
--> Whenever we are doing analysis on the categorical data we will use & undergo with two techniques.
                                 1) countplots

                                 2) pie charts
      
**a)CountPlots**

--> The Purpose of the Categorical data is to distribute the data in the form of bar charts.

--> We will use countplot function which is present in seaborn library to Visualise the data.

--> We can also use the pandas dataframe and the input column provided in the particular data frame to count the frequencies of particular data using value_counts() function Which is a predefined function in pandas library.

--> And to plot the bar graph using the pandas we need to use plot function followed by kind parameter.

**b)Pie Charts**

--> Pie charts Usually show the percentile and pie chart view of the particular data.

--> So we will use the pandas data frame and kind parameter to mention the data as pie.

--> And we will also use the autopct parameter to display the percentage on the pie.

# Univariate Analysis on Numerical data
-->Whenever we relies on the numerical data then we undergo with the 

                  1) Histogram

                  2) Distplot

                  3) Box Plot

**a)Histogram**

--> The purpose of Histogram is used to distrubute the data and also ranges the data

--> To use the Histogram We use predefined function called hist()

--> The predefined Function Histogram Present in the predefined Module Called Matplotlib.pyplot

--> To improve the efficiency of bar charts we can use the bins parameter in the predefined hist function and we can also change the bins value based on the requirement.

**b)Dist Plot**

--> Distplot is also Known as Updated Version of Histogram.

--> Whenever it plots the line to the Histogram, It marks upto the each and every histogram point is also known as **Kernel density Estimation(KDE).**

--> Dist plot is also called as **Probability Density Function(PDF)**, because in the y-axis of the barcharts it shows the probability of the each and every Histogram that lies on the x-axis.

--> So if we want to manipulate the dist plot we use distplot function present in seaborn library.

--> It will also check the skewness of the data.

--> To check the skewness of the data we use predefined function called skew, which is present in pandas library.

**c)Box plot**

--> Box plot is used to give Five Number Summary 

--> Five Number Summary is a part of Statastical data.

![image](https://github.com/mudith-nahata/EDA-Using-Univariate-Analysis/assets/96544398/ea3ba7c9-64b6-44e1-8314-ac5a6bd9de05)


--> So Whatever the data we are having out of min and max is called as **Potential Outliers**.

--> So we can identify and eliminate those data.

--> Median is also called as 50% percentile value in the sorted data.

--> Q1 is also called as 25% percentile value in box plot.

--> Q3 is called as 75% percentile value in box plot.

--> Median data lies between Q1 and Q3.

--> InterQuartile Range consist of Q1 , Q2 and Median 

--> To calculate the Interquartile range formula in box plot is 

                 InterQuartile Range(IQR)=Q3-Q1

--> To calculate the Minimum Value in box plot is

                 Minimum Value=Q1-1.5*(IQR)
                 
                 where,

                      Q1 is 'Minimum Value

                      IQR is 'InterQuartile Range'
                      

--> To Calculate the Maximum Value in box plot is

                    Maximum Value=Q3+1.5*(IQR)
                 
                 where,

                      Q3 is 'Maximum Value

                      IQR is 'InterQuartile Range'
                   




                             
