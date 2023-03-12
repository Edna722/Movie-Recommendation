# Microsoft-Movie-Genre Recommendation
![istockphoto-1202770121-612x612](https://raw.githubusercontent.com/Edna722/Movie-Recommendation/master/New%20folder%20(2)/istockphoto-1202770121-612x612.jpg)

## Overview

Microsoft has been widely known for their lead developer of the personal computer software and applications. From when it was just a mainframe computer programming language used for the early pcs to now becoming the lead experts in top production of software.The starting of the film industry is one of the recent transition the company has implemented. As a beginning  film industry , there is a need for data analyst to help in movie/film recommendation


### Problem Statement 

The main objective is to find the films that are doing the best and this is acheived by analyzing the following:
* The highest profit made throughout the years.
* The company's’ focal point.
* The movies that bring the highest income.
* The top studios and the income generated.
* The top genres and income generated
* Skewerness and kurtosis of the run time

### The Data

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)


### Techniques Used

There are techniques incorporated when performing data 
preparation:
* The missing values were handled by dropping off some
of the columns or filling with mean/median of the data 
depending on the scenario.
* The duplicated values were dropped.
* The cleaned data was the one used in analysis.
* Data visualization was used to answer the problem
statement with the visuals.


## Results 

The highest profit made 
![highest_profit](https://raw.githubusercontent.com/Edna722/Movie-Recommendation/master/New%20folder%20(2)/highest_profit.jpg)

The companys focal point
![top_focus](https://raw.githubusercontent.com/Edna722/Movie-Recommendation/master/New%20folder%20(2)/top_focus.jpg)

Movies that brought the highet income
![top_20_movies](https://raw.githubusercontent.com/Edna722/Movie-Recommendation/master/New%20folder%20(2)/top_20_movies.png)

Top Studios Microsoft can work with.
![top_studios](https://raw.githubusercontent.com/Edna722/Movie-Recommendation/master/New%20folder%20(2)/top_studios.png)

Correlation
![correlation](https://raw.githubusercontent.com/Edna722/Movie-Recommendation/master/New%20folder%20(2)/correlation.png)

Skewerness and Kurtosis
![skewerness_kurtosis](https://raw.githubusercontent.com/Edna722/Movie-Recommendation/master/New%20folder%20(2)/skewerness_kurtosis.png)

## Conclusion
### Microsoft recommendation for the new movie studio would be:
##### 1. Genre Recommendation

The recommendation were based on the total gross made.

-For the single Genre the best recommended are as follow:
  - Family
  - Adventure
  - Fantasy Musical
  
- Multicategory Highly Recommend:
  - Action, Adventure, Scifi
  - Adventure, Animation, Comedy
  - Action, Adventure , Classics and Drama
  
- Genres that also made a huge loss:
  - Action, Adventure, Comedy
  - Action , Adventure ,Scifi
  - Action, Adventure, Drama

##### 2. Target Audience 

The top recommended would be worldwide whcih would be profitable to the company.
Difference between foreign and worldwide sales was 91502365.03702894. Having
movies being released to the domestc audience would incur a significant los..

##### 3. Top Studios to collaborate/ work with:
-These are the top studios:
  -Studio BV
  - Universal Pictures(Uni)
  - Fox
  - Warner Bros(WB)
  - Sony
  - Studio Paramount(Par)
  
##### 4. Being a starting film/movie industry
These would be the to releases that can generate a high income:
   - Avengers: Infinity War
  - Jurassic World
  - Black Panther
  - Furious 7
  - Avengers: Age of Ultron
  - Incredibles 2
  - Jurassic World: Fallen Kingdom
  - Frozen
  - Iron Man 3
  - Rogue One: A Star Wars Story
  
### 5. Next Steps

-Web Scrapping -This is done to obtain the current data from the movie sites so as to carry out analysis with the   precedent/current events.

- Having specificities in terms of giving the specific movie category.

- Coming up with the right predictive model to analyze the movies, improve accuracy and even offer better suggestion  to take.

## 6.  Repository structure
```
├── zippedData                                        <- Both sourced externally
├── New Folder (2)                              <- Both sourced externally and generated from code as images
├── README.md                                   <- The top-level README for reviewers of this project
├── microsoft_film_project.ipynb              <- Narrative documentation of analysis in Jupyter notebook
├── github.pdf                                <- PDF version of Jupyter notebook
├── presentation.pdf                            <- PDF version of project presentation
```