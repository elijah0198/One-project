# Phase 1 Project Description


# MICROSOFT NEW MOVIES STUDIO ANALYSIS


#Author: [***Emmanuel mogoi***](#Emmanuel-mogoi)


## Project Overview

This project analyzes the resource needs of the Austin Animal Center (AAC), which shelters 16,000 animals annually with a No Kill policy. Descriptive analysis of animal intake and outcome data shows that some animals require extended stays and that the number of sheltered animals varies seasonally. The Austin Animal Center can use this analysis to adjust outreach, hiring, and space utilization to improve resource allocation.

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### The Data
In the folder zippedData are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

Because it was collected from various locations, the different files have different formats. Some are compressed CSV (comma-separated values) or TSV (tab-separated values) files that can be opened using spreadsheet software or pd.read_csv, while the data from IMDB is located in a SQLite database.

![movie data erd](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project-v2-4/master/movie_data_erd.jpeg)



## Methods
This project uses descriptive analysis

## Results

Based on the given image, which shows the distribution of genres in movies, it appears that Drama is the most prevalent genre, followed by Comedy and Action. Other genres, such as Horror, Documentary, and Romance, have a relatively smaller percentage of movies.

It's worth noting that the chart may not be an exhaustive representation of all movie genres, as there are many sub-genres and categories within each genre. Additionally, the chart does not provide information on the quality or success of movies within each genre.

Overall, the chart suggests that Drama is the most popular genre among movies, which may reflect the enduring appeal of emotionally engaging stories and characters. Comedy and Action are also popular genres, which may reflect the appeal of escapism, humor, and excitement in movies.

![genre.png.png](https://raw.githubusercontent.com/Lawez/manuu-cahamp/master/images/genre.png.png)



Based on the general trend of the dots in the scatter plot, it appears that there is a positive correlation between a movie's budget and its profit. This makes sense, as movies with higher budgets may have more resources to create compelling stories, characters, and special effects that can attract larger audiences and generate more revenue.

![scatter.png.png](https://raw.githubusercontent.com/Lawez/manuu-cahamp/master/images/scatter.png.png)



The x-axis likely represents the range of movie runtimes, while the y-axis represents the frequency or count of movies in each range. Based on the histogram, it appears that the most common range of movie runtimes is between approximately 90 and 120 minutes. There are also a significant number of movies with runtimes between 120 and 150 minutes, and a smaller number of movies with runtimes outside of this range.

Overall, the histogram suggests that movie runtimes are generally concentrated within a certain range, which may reflect the preferences of audiences and the conventions of the movie industry. However, there is still a significant amount of variation in movie runtimes, indicating that filmmakers and studios have some flexibility in choosing how long to make their movies.

![histogram.png.png](https://raw.githubusercontent.com/Lawez/manuu-cahamp/master/images/histogram.png.png)



## Conclusions

- Based on my findings the following sums up my conclusion:

- These are the top 10 genres;

- Classics|Comedy|Musical and Performing Art

- Drama|Romance

- Drama|Mystery and Suspense

- Action and Adventure|Mystery and Suspense

- Horror

- Musical and Performing Arts

- Action and Adventure|Drama|Horror|Mystery

- Action and Adventure|Classics|Drama|Mystery

- Drama

## Recommendation

- The companies should focus on genrws that incurr a high profit, these are:

- Classics|Comedy|Musical and Performing Art

- Drama|Romance

- Drama|Mystery and Suspense

- Action and Adventure|Mystery and Suspense

- The genres above incurred a profit. The companies should invest in the genres highlighted above.

## Next steps

Perfoming web scraping Using an algorithm or predictive model

## For more information

See the full analysis in the Jupyter Notebook or review this presentation.


## Repositry structure
├── data
├── images
├── presentation
├── README.md
