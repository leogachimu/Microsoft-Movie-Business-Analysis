# MICROSOFT MOVIE STUDIO BUSINESS ANALYSIS
## PROJECT DONE BY: LEONARD MWANGI GACHIMU
![Scenic view of Hollywood](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/14d65c79-e38e-4d71-abe6-152fa8756d61)
## FILM INDUSTRY OVERVIEW
The US film industry aka Hollywood, is the oldest film industry in the world and also the largest in terms of revenue. In 2019, the box office revenue for the USA and Canada was $11.4 billion, a little over 27% of the worldwide revenue of $42.2 billion.

Research also shows that 14% of American watch movies in cinema halls once a month and 46% of adults watch a movie in a cinema hall at least once a year.

The US cinema industry is expected to grow at a Compound Annual Growth Rate (CAGR) of 8.3% by the year 2027 and these are all indicators of a profitable and growing industry that Microsoft can venture into.

Here's deal;

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
![Genre Distribution Based on Two Different Datasets](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/f0c9bf05-8908-4403-87cd-16bc0676eb7a)
4. The top 5 most profitable genres or genre groups are:
   i. Action, Adventure & Sci-Fi - approx. $22.05 billion
   ii. Adventure, Animation & Comedy - approx. $19.842 billion
   iii. Action, Adventure & Fantasy - approx. $7.264 billion
   iv. Action, Adventure & Comedy - approx. $5.662 billion
   v. Drama - approx. $5.307 billion
![Profit Distribution of Top Movie Genres](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/d5b42053-9e3f-49ba-b678-29610ca272ff)
5. The top 5 most profitable movie studios are:
   i. BV (Buena Vista Studios) - approx. $23.835 billion
   ii. Uni. (Universal Studios) - approx. $20.732 billion
   iii. Fox Studios - $19.040 billion
   iv. WB (Warners Bros) - $13.996 billion
   v. Sony - $12.551 billion
   
![Profit Distribution of Major Studios in the Movie Industry](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/edc3dc49-8c4c-4048-801b-ccfca350c4a9)
7. The most productive movie directors include:
   i. Christopher Nolan	- 7 top-rated movies
   ii. Steven Spielberg - 7 top-rated movies
   iii. Martin Scorsese - 7 top-rated movies
   iv. Akira Kurosawa	- 7 top-rated movies
   v. Stanley Kubrick	- 7 top-rated movies
   
![Most Productive Directors in IMDb Top 250 Movies](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/cd7494bf-2332-4f71-8716-ecfaf200da86)

8. The most profitable movie directors include:
   i. Steven Spielberg - approx. $3.327 billion
   ii. Christopher Nolan - approx. $3.195 billion
   iii. Peter Jackson - approx. $2.713 billion
   iv. Anthony Russo - approx. $2.212 billion
   v. Joe Russo - approx. $2.212 billion

![Profit Distribution for Single Movie Directors in IMDb Top 250 Movies](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/bce39aac-af86-4adc-b67c-1baed901d8eb)


9. The correlation between productivity (number of top-rated movies directed) and profitability of a movie director is about 0.6630.
This indicates a moderate correlation and therefore, there is a moderate likelihood that a director with a high number of movies may direct a movie that realizes a high profit margin.

![Number of Movies Vs Total Profit for Top-Rated Movie Directors](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/1d349910-dfb5-413b-a377-2cd2ae33aaaf)


# CONCLUSION
The box office revenue runs into the billions of dollars and is expected to continue growing at an annual rate of 8.3% up to 2027.
It's evident that some genres are more popular than others, with Documentary, Drama, and Comedy each having more than twice the number of movies in any of the other genres. However, a comparison with the genre distribution among IMDb's Top 250 movies list shows that genres such as Adventure, Crime, and Action are popular but not crowded by producers.
Movies that fit the genres of Action, Adventure & Sci-Fi led the pack with a total profit of about $22.05 billion. Only the first 5 genre groups exceeded $5 billion in total profits, so the dominance of certain genres is evident.
The three most profitable movie studios are BV (Buena Vista Studios), Uni. (Universal Studios), and Fox Studios, each raking in about 20 billion dollars in profits. All studios below position 10 made less than 2 billion dollars (less than 10% of the 2 top ranking studios), which shows the dominance of BV (Buena Vista Studios), and Uni. (Universal Studios).
Some movie directors are more productive and/or profitable than others, but the correlation between productivity and profitability is about 0.6630, indicating a moderate correlation. 

# LIMITATIONS
1. I could not determine statistically, the correlation between a genre's popularity and its profitability. This is because most movies fit into multiple genres and in such cases, I could not determine what proportion of a movie's profit can be attributed to a certain genre. I, therefore, analysed the genre-group's profitability as they were, while for popularity, it was possible to split genre groups into separate genres and analyse them separately.
2. A movie’s box office profitability is not simply the difference between the gross revenue and production budget. Research on the Hollywood film industry shows on average, the exhibitor takes nearly half of the gross revenue, and the distributor also takes a cumulative percentage known as ‘distributor rentals’. These ‘cuts’ vary from movie to movie and tend to be higher when a movie is new.
This data was not available, and I computed a movie's profit by simply subtracting the production budget from the worldwide gross revenue.
3. I could not scrape the most up-to-date data from some websites because they required costly subscription plans. These include [IMDb](https://www.imdb.com/) and [Statistica](https://www.statista.com/). Therefore, I had to rely on whatever data I could find on Kaggle. Luckily, for the IMDb Top 250 Movies, I found data on Kaggle dated January 2023.
4. The [home and mobile video entertainment revenue has by far surpassed the box office revenue](https://www.statista.com/statistics/1194522/box-office-home-and-mobile-video-entertainment-revenue-worldwide/).
However, I could not afford the Statistica data about home/mobile video entertainment (Over-the-Top Platforms) market worldwide from 2015 to 2021, so my analysis cannot provide Microsoft with data-driven advice on whether they should focus more on theatre distribution or streaming of their movies.


# RECOMMENDATIONS
People across America are still going to watch movies in cinema halls and therefore Microsoft has made the right decision to venture into the film industry.


## Deliverables

There are three deliverables for this project:

* A **GitHub repository**
* A **Jupyter Notebook**
* A **non-technical presentation**

Review the "Project Submission & Review" page in the "Milestones Instructions" topic for instructions on creating and submitting your deliverables. Refer to the rubric associated with this assignment for specifications describing high-quality deliverables.

### Key Points

* **Your analysis should yield three concrete business recommendations.** The ultimate purpose of exploratory analysis is not just to learn about the data, but to help an organization perform better. Explicitly relate your findings to business needs by recommending actions that you think the business (Microsoft) should take.

* **Communicating about your work well is extremely important.** Your ability to provide value to an organization - or to land a job there - is directly reliant on your ability to communicate with them about what you have done and why it is valuable. Create a storyline your audience (the head of Microsoft's new movie studio) can follow by walking them through the steps of your process, highlighting the most important points and skipping over the rest.

* **Use plenty of visualizations.** Visualizations are invaluable for exploring your data and making your findings accessible to a non-technical audience. Spotlight visuals in your presentation, but only ones that relate directly to your recommendations. Simple visuals are usually best (e.g. bar charts and line graphs), and don't forget to format them well (e.g. labels, titles).

## Getting Started

Please start by reviewing this assignment, the rubric at the bottom of it, and the "Project Submission & Review" page. If you have any questions, please ask your instructor ASAP.

Next, we recommend you check out [the Phase 1 Project Templates and Examples repo](https://github.com/learn-co-curriculum/dsc-project-template) and use the MVP template for your project.

Alternatively, you can fork [the Phase 1 Project Repository](https://github.com/learn-co-curriculum/dsc-phase-1-project), clone it locally, and work in the `student.ipynb` file. Make sure to also add and commit a PDF of your presentation to your repository with a file name of `presentation.pdf`.

## Project Submission and Review

Review the "Project Submission & Review" page in the "Milestones Instructions" topic to learn how to submit your project and how it will be reviewed. Your project must pass review for you to progress to the next Phase.

## Summary

This project will give you a valuable opportunity to develop your data science skills using real-world data. The end-of-phase projects are a critical part of the program because they give you a chance to bring together all the skills you've learned, apply them to realistic projects for a business stakeholder, practice communication skills, and get feedback to help you improve. You've got this!
