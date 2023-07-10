## Tableau Dashboard to analyze Financial and Literary Trends in the Movie Industry

**Goal:** Giving an insight into literary and financial aspects of the movie industry.

**Queries to Answer:**
- What was the financial performance of movies from 1980 to 2020?
- How was quality of movies produced by top 5 companies over the last four decades?
- How the popularity of the genre has progressed over the period of 40 years?
- Which are the emerging countries in movie production besides the United States?

**Data:** This dataset was created by Daniel Grijalva and focuses on movies produced from 1980 to 2020. The dataset was scraped from IMDB using Python.  You can download dataset from [Kaggle](https://www.kaggle.com/datasets/danielgrijalvas/movies)

**For the final dashboard please refer to [Dashboard](/Dashboard.pdf)**

**Visualization 01:**<br>
The first visualization in the dashboard depicts the financial performance giving a brief idea about the Gross, Budget and Profit (calculated field) of the movies produced over the years. The Bar-in-bar chart gives a great comparison of the difference between Gross and Budget providing a holistic view of how economically profitable movie industry is to the Financial Investors. The line chart illustrated the Profit trend of the industry. It will furnish the target audience with the prediction for expected amount of profit that the movie industry will deliver in the upcoming years based on the relative trend and aid them with decisions concerning investment opportunities.
![Image01](/Data/Images/V01.png)

**Visualization 02:**<br>
The second visualization depicts a comparison of the financial performance of top production companies over the years. In order to get the top performing countries, all the subsidiaries of the companies were grouped together and the top 5 companies were then filtered out based on their financial performance throughout the period. The rest of the companies have been grouped together under the name of ‘Others’. The bar chart below gives a holistic view of the average score received by the top 5 companies over the period. It also gives an idea that even the companies performing financially good over the years have scored low based on the content and other related factors. Online streaming platform can use the information to plan the investment in production companies scored well and have showed a positive trend over the years. This graph can also provide movie enthusiasts and film historians with ample information to filter down few production companies whose movies they can enjoy when looking for older archives of movies.
![Image01](/Data/Images/V02.png)

**Visualization 03:**<br>
The third visualization gives a comprehensive view of the genres of movies that have been produced over the time period. It also highlights the most prominent genres, their variation and other genres that have recently been preferred by movie producers and viewers. This graph will give online streaming platforms an idea about the kind of movies viewers will prefer and design a recommendation system based on the genres they prefer. Movie enthusiasts can use this graph to seek idea on which genres of movies were preferrable during earlier period.
![Image01](/Data/Images/V03.png)

**Visualization 04:**<br>
The fourth visualization gives a geographical view of the genres that have been produced in various countries. The map also has a filter which can be used to view the progression of a single or more than genres over the time-period. The map provides production houses with guidance on which country’s audience they should target based on the genres of movies favored by them.
![Image01](/Data/Images/V04.png)

**Visualization 05:**<br>
The fifth visualization is a Choropleth Map which represents the emerging countries in the movie industry based on the number of movies produced in the countries. This map excludes the United States and the United Kingdoms as these are major contributors and focuses on the countries which are trying to surface in this field. This map will be a major help to both production houses and online streaming platforms to offer information about the untapped market opportunities they can explore.
![Image01](/Data/Images/V05.png)