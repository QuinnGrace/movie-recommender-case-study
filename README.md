# Creating a Movie Recommender System Using Machine Learning Case Study

NOTE: Due to the nature of this project, code cannot be shared publicly. 

## Context 
A movie-streaming service has low customer retention due to having no recommender system, which competitors in the industry have. They need a movie-recommender system to stay competitive.

## Expected Outcomes
- Identify trends in movie watching
- Create a movie recommender system
- Create an app that integrates the movie recommender system
- Report findings to stakeholders

## Tools Used
- Python
  - Streamlit
  - scikit-learn
  - nltk
- Comet
- GitHub
- AWS EC2 with S3 bucket

## Output
A demo of the app created:


https://github.com/QuinnGrace/movie-recommender-case-study/assets/73368635/11cc862f-71bf-4d54-ac78-18ea0604ad34

A bar graph showing the amount of ratings given by the top users:

![image](https://github.com/QuinnGrace/movie-recommender-case-study/assets/73368635/e260e70f-2136-48bd-bb09-a59c9f941c66)

A pie chart showing the distribution of ratings:
 ![image](https://github.com/QuinnGrace/movie-recommender-case-study/assets/73368635/fb0819ff-424d-494d-bace-5732f5978a59)

A bar graph showing the number of ratings given to the top 20 movies:
![image](https://github.com/QuinnGrace/movie-recommender-case-study/assets/73368635/5c82250c-0a87-4762-8840-c5c1f60e61fe)


## Conclusions
- The top users have given a disproportionate number of ratings. If not handled carefully, this could skew the data towards their personal preferences.
- Users tended to give high ratings and low ratings were rare, this means we have little data on what users do not like.
- The top movie gained a lot of ratings, whereas many movies only received 1 rating. Movies with only 1 rating have their rating decided essentially by one user's preference, which is far from ideal

## Recommendations
- Encourage users to rate movies. Especially movies with few ratings and users who do not rate often. This should help even the data out.
- When users do not enjoy movies, they are unlikely to rate them but we need this data as it is as relevant to a person's taste as what they enjoy. Perhaps watch time should be taken into account and films with low times (i.e. people stop watching them early) are counted as not enjoyed to gather this data.

## Acknowledgements
I would like to thank my team members for their contributions:
- Bankole Ridwan (Team Lead)
- Tioluwatise Onadipe (Administrative Lead)
- Kennedy Chege (Technical Lead)
- Chidimna Madukife
