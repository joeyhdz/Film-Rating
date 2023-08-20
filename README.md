# Introduction
In this project, we delve into the world of ratings and reviews, aiming to uncover insights similar to those highlighted in the FiveThirtyEight article on Fandango movie ratings. Our project examines the discrepancies, trends, and potential biases in ratings across different platforms.

[FiveThirtyEight Article Here](https://fivethirtyeight.com/features/fandango-movies-ratings/)

# Project Goals
1. Distribution Analysis: We will examine the distribution of ratings across platforms, exploring factors such as average ratings, median ratings, and overall distribution shape.
2. Comparative Analysis: Our project will focus on comparing the rating distributions between different platforms. We will use visualizations and statistical measures to highlight any significant differences and trends.

# Tools 
 - Programming Language: Python
 - Data Manipulation: Pandas
 - Data Visualization: Matplotlib, Seaborn
 - Statistical Analysis: Scipy, Statsmodels

<hr> 
# Getting Started: Fandango

![Untitled](https://github.com/joeyhdz/Film-Rating/assets/81498617/375c7742-ab23-4bd8-b826-5da72a6a03ab)

![Untitled](https://github.com/joeyhdz/Film-Rating/assets/81498617/2a9f3775-8a90-457b-a8ed-428cf9dc0a73)

# How many films are in the Fandango DF for each year? 

![Untitled](https://github.com/joeyhdz/Film-Rating/assets/81498617/40b1a4ef-c95b-497a-881c-bc81b8b121c0)

## As noted in the article, due to HTML and star rating displays, the true user rating may be slightly different than the rating shown to a user. Let's visualize this difference in distributions.
![Untitled](https://github.com/joeyhdz/Film-Rating/assets/81498617/e8a8582c-1d1d-4433-bb44-10f22a47f5fc)

## Now we will quantify this discrepancy by creating a new column of the different between STARS displayed versus true RATING then creating a plot to display the number of times these differences occur.

![Untitled](https://github.com/joeyhdz/Film-Rating/assets/81498617/90c7958d-1115-4435-89e3-5e14cc487a34)


# Rotten Tomatoes: Compare Ro.Tom. Critic Reviews vs Rot. Tom. User Reviews

![Untitled](https://github.com/joeyhdz/Film-Rating/assets/81498617/11732a12-cb17-4d33-baa4-850fb06d912f)

# Metacrit. User Ratings vs Metacrit. Ratings

![Untitled](https://github.com/joeyhdz/Film-Rating/assets/81498617/ec0b7748-3d39-4378-b8fd-ca3cffe63e9c)

# IMDB User Votes vs MC User Votes

![Untitled](https://github.com/joeyhdz/Film-Rating/assets/81498617/a5d3cc51-ba27-49c5-b1a9-81264786a94d)


# Distribution of Scores Across All Sites
![Untitled](https://github.com/joeyhdz/Film-Rating/assets/81498617/305dc6f0-e486-49a3-8339-66acd704da44)

![Untitled](https://github.com/joeyhdz/Film-Rating/assets/81498617/72857f5d-422b-4d59-8db0-c54738b6e93c)

# Looking at a Cluster map of the worst films across all platforms
![Untitled](https://github.com/joeyhdz/Film-Rating/assets/81498617/6cff9e74-c1df-4458-b5a2-bb7ac0150e3d)
The clustermap visualization revealed a distinct pattern in the ratings data among the analyzed platforms. Notably, Fandango's ratings stood out as consistently higher in comparison to other sites. This trend was particularly pronounced when considering that Fandango often rounded up ratings to the nearest half-star. This observation suggests a potential bias or leniency in Fandango's rating system, wherein movies may receive higher ratings than they would on other platforms, possibly influencing users' perceptions and choices. This discrepancy emphasizes the need for further investigation into Fandango's rating practices and their implications for users seeking accurate and unbiased movie ratings.

# Rotten Tomatoes top 10 lowest rated films (based off Critic ratings)
**![image](https://github.com/joeyhdz/Film-Rating/assets/81498617/22be224e-3ae3-44e9-bf6f-0b8dcafac791)

# Rating Distribution for Various Platforms Using Rotten Tomatoes 10 Worst Reviewed Films
![Untitled](https://github.com/joeyhdz/Film-Rating/assets/81498617/975b66d6-ed84-439f-a8f4-45da80cf8218)


