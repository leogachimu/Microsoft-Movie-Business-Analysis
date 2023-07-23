![image](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/7605781b-b96b-4236-b51a-ad56194f45a0)# MICROSOFT MOVIE STUDIO BUSINESS ANALYSIS
## PROJECT DONE BY: LEONARD MWANGI GACHIMU
![Scenic view of Hollywood](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/14d65c79-e38e-4d71-abe6-152fa8756d61)
## FILM INDUSTRY OVERVIEW
The US film industry aka Hollywood, is the oldest film industry in the world and also the largest in terms of revenue. In 2019, the box office revenue for the USA and Canada was $11.4 billion, a little over 27% of the worldwide revenue of $42.2 billion.

Research also shows that 14% of American watch movies in cinema halls once a month and 46% of adults watch a movie in a cinema hall at least once a year.

The US cinema industry is expected to grow at a Compound Annual Growth Rate (CAGR) of 8.3% by the year 2027 and these are all indicators of a profitable and growing industry that Microsoft can venture into.

Here's the deal;

Microsoft is not a company that jumps into what everyone else is doing.

There has to be vision, relevant data, analysis of the data, and data-driven strategy.

This is what this report is all about.

## PROJECT OVERVIEW

In this project, I used my data science skills to extract, explore, clean, wrangle, visualize, and interpret the data relevant to helping Microsoft set up a successful movie studio. 

## BUSINESS PROBLEM

Microsoft intends to set up a movie studio but they don't have prior experience in movie production. I was charged with analysing data from the movie industry and developing strategic and actionable insights into the type of films they should produce, the competition, and the talent they should hire. 
![Steven Spielberg winning Oscar Awards](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/187682bb-7c57-4223-b2ea-148343fe2d59)
                                                              Oscar Awards here we come
## PROJECT SCOPE
1. To find out the most popular genres based on the total number of movies produced.
2. To find out the most popular genres based on the IMDB Top 250 Movies.
3. To evaluate content gaps between what every movie studio is producing and the genres that are winning the Top 250 rating.
4. To find out the most profitable genres or genre groups.
5. Competitor analysis of the most profitable movie studios in 2019.
6. To find out the top 15 best-performing movie directors.
7. To find out the top 15 most profitable movie directors.
8. To analyse the correlation between productivity (number of top-rated movies directed) and profitability of a movie director.
   
## THE DATASETS USED
For this project, I used the following datasets:
i.) imdb.title.basics.csv - provided
This dataset was obtained from the IMDb database of all movies in 2019.
ii.) movies.csv - downloaded from [Kaggle](https://www.kaggle.com/datasets/ashishjangra27/imdb-top-250-movies)
iii.) bom.movie_gross.csv - provided
iv.) tn.movie_budgets.csv - provided
v.) BOM_1000_movies_df - scraped from [Box Office Mojo](https://www.boxofficemojo.com/chart/ww_top_lifetime_gross/?area=XWW)

## METHODOLOGY
Execution of the project involved the following:
### Data Understanding
I explored the datasets to understand their schema, size, data types, and examine the presence of invalid or inconsistent data such as missing values, duplicates, placeholders, and outliers.
### Data Analysis
I transformed the data into DataFrames using the Pandas library in Python and I performed different transformations and analyses to suit my goals.
### Data Visualization
I used various visualization methods such as bar plots, histograms, and scatter plots to display my findings and facilitate interpretation.
### Data Interpretation
I interpreted the various findings and visualizations to build a recommendation for Microsoft.

## THE FINDINGS
1. I found out that the most popular genres based on the number of movies produced (movie data from IMDb database), include:
   - Documentary
   - Drama
   - Comedy
   - Thriller
   - Horror and
   - Action
     
![Most Popular Genres Based on Number of Movies Produced](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/29d20ac4-2207-43c2-93ee-7be2d386fa02)

2. The most popular genres based on the IMDb Top 250 Movies include:
   - Drama
   - Adventure
   - Crime
   - Action
   - Comedy
   - Mystery
     
![Most Popular Genres Based on IMDb Top 250 Movies](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/c407a0db-d33b-401e-a32d-07d22ae3c356)

3. The top 250 movies list is the most reliable guide for consumer trends and by plotting the two bar charts on the same figure, we can see Drama is by far the most popular genre but also one of the most crowded. Adventure, Crime, and Action are also popular but are not as crowded as Drama in terms of content.

![Top Genres Based on Number of Movies](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/464ed0be-2148-4e83-84f5-707450e4c140)


4. The top 5 most profitable genres or genre groups are:

   i. Action, Adventure & Sci-Fi - approx. $22.05 billion
   ii. Adventure, Animation & Comedy - approx. $19.842 billion
   iii. Action, Adventure & Fantasy - approx. $7.264 billion
   iv. Action, Adventure & Comedy - approx. $5.662 billion
   v. Drama - approx. $5.307 billion

![Top 5 Most Profitable Movie Genres](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/ee9ba833-4436-4485-939d-7b34c969f20c)


5. The top 5 most profitable movie studios are:

   i. BV (Buena Vista Studios) - approx. $23.835 billion
   ii. Uni. (Universal Studios) - approx. $20.732 billion
   iii. Fox Studios - $19.040 billion
   iv. WB (Warners Bros) - $13.996 billion
   v. Sony - $12.551 billion
   
![Top 5 Most Profitable Movie Studios](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/5c49be67-147c-4dca-a4e7-2dd72ef3bf27)


6. The most productive movie directors include:

   i. Christopher Nolan	- 7 top-rated movies
   ii. Steven Spielberg - 7 top-rated movies
   iii. Martin Scorsese - 7 top-rated movies
   iv. Akira Kurosawa	- 7 top-rated movies
   v. Stanley Kubrick	- 7 top-rated movies
   
![Most Productive Directors in IMDb Top 250 Movies](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/cd7494bf-2332-4f71-8716-ecfaf200da86)

7. The most profitable movie directors include:

   i. Steven Spielberg - approx. $3.327 billion
   ii. Christopher Nolan - approx. $3.195 billion
   iii. Peter Jackson - approx. $2.713 billion
   iv. Lee Unkrich - approx. $1.446 billion
   iv. Anthony Russo - approx. $1.222 billion
   v. Joe Russo - approx. $1.222 billion

![Profit Distribution for Single Movie Directors in IMDb Top 250 Movies](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/bce39aac-af86-4adc-b67c-1baed901d8eb)


8. The correlation between productivity (number of top-rated movies directed) and profitability of a movie director is about 0.6630.
This indicates a moderate correlation and therefore, there is a moderate likelihood that a director with a high number of movies may direct a movie that realizes a high profit margin.

![Number of Movies Vs Total Profit for Top-Rated Movie Directors](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/1d349910-dfb5-413b-a377-2cd2ae33aaaf)


## CONCLUSION
The box office revenue runs into the billions of dollars and is expected to continue growing at an annual rate of 8.3% up to 2027.

It's evident that some genres are more popular than others, with Documentary, Drama, and Comedy each having more than twice the number of movies in any of the other genres. However, a comparison with the genre distribution among IMDb's Top 250 movies list shows that genres such as Adventure, Crime, and Action are popular but not crowded by producers.

Movies that fit the genres of Action, Adventure & Sci-Fi led the pack with a total profit of about $22.05 billion. Only the first 5 genre groups exceeded $5 billion in total profits, so the dominance of certain genres is evident.

The three most profitable movie studios are BV (Buena Vista Studios), Uni. (Universal Studios), and Fox Studios, each raking in about 20 billion dollars in profits. All studios below position 10 made less than 2 billion dollars (less than 10% of the 2 top ranking studios), which shows the dominance of BV (Buena Vista Studios), and Uni. (Universal Studios).

Some movie directors are more productive and/or profitable than others, but the correlation between productivity and profitability is about 0.6630, indicating a moderate correlation.

## MOVIE STUDIO BUSINESS STRATEGY RECOMMENDATIONS FOR MICROSOFT
1)	Microsoft shouldn’t jump into what everyone is doing, whether they’re succeeding or not.
   
2)	I recommend Drama, Adventure, Crime, Action, and Comedy as the best 5 	genres for Microsoft as a beginner studio.
   
3)	Competitor analysis reveals that the market has a few dominant studios. I, therefore, urge Microsoft to conduct further analysis of these top studios, including their technology, marketing strategies, and SWOT analysis.
    
4)	Further analysis of BV Studio shows that it made an average profit of about $567 million per genre. Microsoft should target at least $600 million per genre.
   
5)	When it comes to hiring the best talent, Microsoft should focus more on hunting down the best director the world can offer and seek their advice on hiring the rest of the team.
   
6)	The correlation between productivity and profitability of a movie is moderate. Microsoft should engage any of the most profitable directors, regardless of the number of movies they have directed.
   
7)	I recommend the following movie directors: Steven Spielberg, Christopher Nolan, Peter Jackson, Lee Unkrich, Anthony Russo, and Joe Russo.

## STUDY LIMITATIONS
1) I could not determine statistically, the correlation between a genre's popularity and its profitability.
   
2) Data about exhibitor rates and distributor rentals was not available, so I computed a movie's profit by simply subtracting the production budget from the worldwide gross revenue.
   
3) I could not scrape the most up-to-date data from some websites because they required costly subscription plans.

4) The home and mobile video entertainment revenue has by far surpassed the box office revenue. However, I could not afford the Statistica data about home/mobile video entertainment.
   
## RECOMMENDATIONS FOR FUTURE ANALYSIS
1) Future studies should come up with a criterion or data for computing a list of the most profitable single genres.
   
2) Analysis should be done on the latest data on home/mobile video entertainment (Over-the-Top Platforms) market.
   
3) Accurate data about exhibitor rates and distributor rentals should be sought, to enable computation of the accurate profit per movie, genre, studio, or director.
   
4) To find the correlation between a movie’s rating on IMDb and other ranking websites such as Rotten Tomatoes and The Numbers.

## PROJECT DELIVERABLES
There are three deliverables for this project:
* A **GitHub repository**
* A **Jupyter Notebook**
* A **non-technical presentation**



