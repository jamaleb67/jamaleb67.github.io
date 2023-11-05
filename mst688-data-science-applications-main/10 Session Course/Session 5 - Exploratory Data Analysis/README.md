##### [Youtube/GDP](Top)

<img src=https://i.imgur.com/ACFFpv2.png width=1500 class="center">
<h1 align="center">Top Youtubers effecting GDP between 2019 - 2022??</h1>
    
    In today's world, the internet has become an integral part of our lives. With the rise of online platforms such as YouTube, it has become easier than ever for people to access information and entertainment from all over the world. At the same time, Gross Domestic Product (GDP) remains one of the most widely used indicators of economic performance. In this project, we aim to explore the relationship between these two seemingly unrelated topics: GDP and YouTube. By analyzing data on GDP and YouTube usage patterns, we hope to gain insights into how these two factors are connected and what implications this may have on our understanding of the modern world.

The objective of this project is to analyze the relationship between GDP and YouTube usage patterns. We will use data on GDP and YouTube usage patterns to gain insights into how these two factors are connected and what implications this may have on our understanding of the modern world.

Our goal is to answer the following questions:

- What are the the top Youtubers in countries around the globe?
- What is the Top GDP countries, and what is there growth during COVID?
- Is there a correlation between Top Youtubers and selected GDP Nations?
- What is statistical corelations can be made?

To answer these questions, we will use Python and its data analysis libraries, such as Pandas and Matplotlib. We will start by importing the dataset and cleaning the data, followed by exploratory data analysis and visualization.

I will be using the following datasets: 
- [Top Youtubers](https://www.kaggle.com/mdhrumil/top-5000-youtube-channels-data-from-socialblade)
- [GDP](https://www.kaggle.com/fernandol/countries-of-the-world)

APIs:
- [YouTube API](https://developers.google.com/youtube/v3/docs/channels/list)
- [Google API](https://console.cloud.google.com/apis/library/youtube.googleapis.com)


# Table of contents <a class='anchor' id='top'>
- [Introduction](#Introduction)
- [Import libraries](#import)
- [Load data](#load_data)
- [GDP Analysis](#gdpproject)
- [Bar chart](#bar_chart)
- [GDP Conclusion](#geo)
- [YouTube Analysis](#Analysis)
- [Youtube API](#YouTube)
- [Conclusion](#Conclusion)

# Introduction  <a class='anchor' id='Introduction'>

# Import libraries <a class='anchor' id='import'>


<p align="center">
  <b><u><span style="font-size: 24px">
  GDP Analysis from 2019 - 2020<a class='anchor' id='gdpproject'></span></u></b><br>
</p>

### Load data <a class='anchor' id='load_data'>

In load data a CSV file named "GDP by Country 1999-2022.csv" was put into a pandas dataframe named "data". It then removed any double quotes and commas from the data. Finally, it sets the display options to show all columns and rows, and prints a summary of the data using the describe() method.

I observe the data read in from the CSV file. I see that there are 227 rows and 20 columns. I also see that there are some missing values in the data. I will need to clean the data before I can use it for further analysis or to merge more data to it.
    
### Bar chart for GDP by Country 1999-2022

The Bar chart is skewed to the right by the United States and China. The United States has a GDP of 21.44 trillion dollars, while China has a GDP of 14.34 trillion dollars. The United States and China are the only two countries with a GDP of over 10 trillion dollars. The next highest GDP is Japan with a GDP of 5.08 trillion dollars.

All other Top ten countries combined would not equal the U.S. GDP. The U.S. GDP is 21.4 times higher than the tenth highest GDP, Canada.

### 2022 GDP for germany, south korea, UK, US, Mexico, japan and india

 I used pandas and seaborn libraries to analyse and visualize the Gross Domestic Product (GDP) for Seven Countries. The data was collected from the World Bank and the International Monetary Fund (IMF). The larger dataset was filtered and the filtered data is stored in the Countries dataframe.

The Countries dataframe is sorted on 2022 column and than again stored in a new dataframe.  

The selected countries are Germany, South Korea, United Kingdom, United States, Mexico, Japan and India. 

The data is visualized using a bar chart. The bar chart shows the GDP for the selected countries in 2022.

## 📈 Gross Domestic product average for 2019 - 2020 <a class='anchor' id='19-20'>
+ Germany, South Korea UK, US, Mexico, Japan and India



The GDP for the selected countries is visualized using a bar chart. The bar chart shows the GDP for the selected countries in 2019 - 2020.

The code uses a familar dataframe 'countries' and uses the melt function. Country is the id_var and the years are the value_vars. The years are renamed to 'year' and the GDP is renamed to 'gdp'. 
