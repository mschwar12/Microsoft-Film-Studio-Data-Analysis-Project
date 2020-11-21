# Microsoft Film Studio Data Analysis Project

**Author**: [Matt Schwartz](mailto:mtschwart@gmail.com)

## Overview 

The following report provides data and insights on the film industry by exploring what success looks like, and what areas are worth pursuing.

## Business Problem

Microsoft has decided to enter the movie business, but where to start? Microsoft is already well integrated in millions of homes across the country with its Office software in virtually every PC. The company also maintains a vast entertainment business with Xbox and its associated game studio.

To diversify its offerings in the entertainment space, it makes sense to enter the filmmaking industry. As streaming grows and traditional TV viewing shrinks, platforms are starved for any content they can get their hands on. Microsoft can further expand its market share by becoming a content provider. Their films can start in theaters, and then be pushed to its Xbox service, or any others who are interested in its productions.

## Data

Four main data sets from 3 sources were used to conduct analysis on the film industry. These were:
    - [IMDB](https://www.imdb.com/interfaces/)
    - [Box Office Mojo](https://www.boxofficemojo.com/)
    - [The Numbers](https://www.the-numbers.com/)

This data provided useful information like production budgets, domestic and foreign gross revenues, and average ratings for each film.

## Methods

To glean meaningful insights from the data, only movies made between 2010 and 2019 were considered. The film industry in this decade is significantly different than previous decades in terms of the size of proudctions and the types of movies made.

The data allowed for genre-specific analysis, what movies cost the most and how budgets have changed over time, and what sort of connections there exist between budgets, ratings, and gross revenues.

## Results

We find that average rating and total revenues are highly correlated.

![ratings and revenues](http://localhost:8888/view/Microsoft-Film-Studio-Data-Analysis-Project/images/ratings_revenue.png)

Average budgets are increasing year-over-year.

![budgets_year](http://localhost:8888/view/Microsoft-Film-Studio-Data-Analysis-Project/images/budgets_year.png)

The average rating for the top ROI movies is well below those of the top grossing

![rating_roi](http://localhost:8888/view/Microsoft-Film-Studio-Data-Analysis-Project/images/ratings_roi.png)

![rating_top_gross](http://localhost:8888/view/Microsoft-Film-Studio-Data-Analysis-Project/images/ratings_top_gross.png)

## Conclusions

This analysis led to a number of useful findings:
- Dramas are far and away the most frequent type of movie produced. However, they are not the most lucrative. Adventure, animation, sci-fi, action, and fantasy rake in the most cash.
- We see a strong, positive correlation between budgets and revenues. Movies that tend to spend a lot, also make a lot of money, though this subject could use further analysis
- Average budgets per year are increasing while the number of movies produced a year are slightly decreasing. It's possible that that larger productions and their profitability are discouraging studios from financing smaller movies, that may have equal returns on their investment, but don't earn as much overall.
- There is a clear, strongly positive correlation between revenues and average ratings. This deserves further analysis, but if your movie is rated highly and the production budget was large, chances are the movie is making a lot of money.
- We found a negative correlation between ROI and average rating. This might just be noisy data but it does tell us that ROI has no real connection to ratings, nor does it with how much a movie will earn. The top ROI movies rated significantly worse than the top grossing movies

## Further Analysis

We could glean some addidtional insights from this data by increasing the rigour of our statistical analysis. Some areas I'd like to explore:

- Is the decreasing number of movies being produced a blip or a trend, and are growing production budgets in some way causing this to happen?
- Is there any sort of causation between average ratings and revenues? What other factors lead to high average ratings? Is there a way to engineer movie production to create only high rating movies?
- To what extent does there exist some causation between production budgets and average rating? We found a weak but positive correlation. At what spend threshold do we begin to see diminishing marginal returns?
- Would we see a positive correlation between ROI and ratings if we removed horror and mystery films? To what extent is there a real connection there?

## For More Information

Please find the full analysis in the Jupyter notebook contained in this respository.

For any questions, please contact Matt Schwartz at [mtschwart@gmail.com](mailto:mtschwart@gmail.com)




## Repository Structure

```
├── data
├── images
├── README.md
├── Microsoft_Film_Studio_Project_Submission.pdf
└── Microsoft_Film_Studio_Project_Submission.ipynb
```