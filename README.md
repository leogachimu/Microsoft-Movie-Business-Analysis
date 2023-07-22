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
   i. Action, Adventure & Sci-Fi
   ii. Adventure, Animation & Comedy
   iii. Action, Adventure & Fantasy
   iv. Action, Adventure & Comedy
   v. Drama
![Profit Distribution of Top Movie Genres](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/d5b42053-9e3f-49ba-b678-29610ca272ff)
5. The top 5 most profitable movie studios are:
   i. BV (Buena Vista Studios)
   ii. Uni. (Universal Studios)
   iii. Fox Studios
   iv. WB (Warners Bros)
   v. Sony 
![Profit Distribution of Major Studios in the Movie Industry](https://github.com/leogachimu/Microsoft-Movie-Business-Analysis/assets/122081776/edc3dc49-8c4c-4048-801b-ccfca350c4a9)



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
