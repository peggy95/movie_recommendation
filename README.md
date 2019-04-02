# movie_recommendation
-- course final project

## Background
This project is a final project which aimed at practicing data processing skills and learning shllow learning.
So this is not a classical recommendation engine which uses MF, GBDT+LR etc.. We recommend movies for movies in consideration of movie context. Uses' information is rarely used.
The most intersting part here are to reduce the number of keywords using ntlk and to analysis the actors and directors' social network. 

For now, I'd better to use more advanced methods to solve this problem such as Collaborative Filtering and deep networks (deep and wide) to recommend movies to users based on users' historical behaviours.

## Dataset Information
We make recommendations using the content of the TMDB dataset that contains around 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts and vote averages.

## System Mechanism
In practice, recommendation engines are of three kinds:

⋅⋅*popularity-based engines: usually the most simple to implement be also the most impersonal
⋅⋅*content-based engines: the recommendations are based on the description of the products
⋅⋅*collaborative filtering engines: records from various users provide recommendations based on user similarities
We aimed to model an engine for recommendation of movies based on several aspects such as popularity, similarity. We would like to find similar items by using a similarity metric. Once we have the matrix, we use it to determine the best recommendations for a user based on the movies he has already liked and watched. In other words, our engine bases on popularity and content.

## Recommendation Process
Basically,our system will work as follows: after the user has provided the name of a film he liked, the engine should be able to select in the database a list of 5 films that the user will enjoy. These files contain metadata for all 45,000 movies.

## Folders
codes is the folder containing jupyter notebook file while data here is not correct now. You can check the jupyter notebook to find the website to download. PPT is the presentation materials.
