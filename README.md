# Box-Office-Prediction
This repository contains the dataset used for training an ML model to predict the box office success (revenue) from other parameters, such as Genre, Budget, Popularity, Star Power, etc.

The data was taken from various TMDB datasets found on Kaggle, and then further run through the [TMDB](https://www.themoviedb.org/) and [OMDB](https://omdbapi.com/) APIs to fetch data for all features. Some the movies were also extracted from the TMDB Dataset through it's APIs directly.

The dataset has 6065 movies in total, with the following features:

1. Genres
2. ID
3. Original Language
4. Original Title
5. Overview
6. Popularity Rating
7. Release Date
8. Title
9. TMDB Rating
10. TMDB Vote Count
11. IMDb ID
12. Budget
13. Revenue
14. Production Companies
15. Cast
16. Crew
17. Production Countries
18. Spoken Languages
19. Runtime
20. Tagline
21. MPAA Rating
22. IMDb Rating
23. IMDb Vote Count
24. Star Power

The popularity index of the most popular actor in the movie was taken to be the *Star Power*. The IMDb Ratings and Vote Count was taken from the OMDB API, along with the MPAA rating.

