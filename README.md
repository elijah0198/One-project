
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

## Methods
This project uses descriptive analysis

## Results


![genre.png.png](https://raw.githubusercontentcom/elijah0198/MICROSOFT-S-NEW-MOVIE-STUDIO/master/images/genre.png.png)




![scatter.png](https://raw.githubusercontentcom/elijah0198/MICROSOFT-S-NEW-MOVIE-STUDIO/master/images/scatter.png)




![scatter.png](https://raw.githubusercontentcom/elijah0198/MICROSOFT-S-NEW-MOVIE-STUDIO/master/images/scatter.png)



## Conclusions
This analysis leads to three recommendations for improving operations of the Austin Animal Center:

Engage in targeted outreach campaigns for dogs that have been sheltered at AAC for more than 30 days. While most dogs will have been placed after 30 days, this may help reduce the number of dogs that end up having extended stays, potentially requiring many more months of care.
Reduce current spending until the numbers of intakes and sheltered animals return to normal. Given the reduced activity during this period, AAC should consider ways to temporarily reduce costs by changing space utilization or staffing.
Hire seasonal staff and rent temporary space for May through December. To accommodate the high volume of intakes and number of sheltered animals in the spring and fall, AAC should leverage seasonal resources, rather than full-year ones. This will allow AAC to cut back on expenditures during the months when there is lower
Next Steps

## Nextsteps
Further analyses could yield additional insights to further improve operations at AAC:

Better prediction of animals that are likely to have long stays. This modeling could use already available data, such as breed and intake condition.
Model need for medical support. This modeling could predict the need for specialized personnel to address animals' medical needs, including neutering, using intake condition and sex data.
Predicting undesirable outcomes. This modeling could identify animals that are more likely to have undesirable outcomes (e.g. Euthanasia) for targeted medical support or outreach.


## For more information
See the full analysis in the Jupyter Notebook or review this presentation.

For additional info, contact Alison Peebles Madigan at alison.peeblesmadigan@flatironschool.com

## Repositry structure
├── data
├── images
├── README.md
├── Animal_Shelter_Needs_Presentation.pdf
└── animal_shelter_needs_analysis.ipynb