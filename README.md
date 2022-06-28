# moviezrecommendersystem
This is content based recommender system which recommands the movie on the basis of tags of the movie you searched form the database of 5000 movies. The tags include genre of the movie, director, lead roles, and many more. And calculate the cosine similarities between the searched movie and the rest of the 4999 movies and show the top 5 similar movies to that of searched movie.
![image](https://user-images.githubusercontent.com/72484173/176251472-24283b43-fa88-492c-936c-ee794a98b6f0.png)
![image](https://user-images.githubusercontent.com/72484173/176251640-29a9bfa6-ed50-4bf5-8e76-a869e8f87dba.png)

In this project I have used 2 datasets of movies from tmdb website and menupulated the data according to the requirements and make tags on the basis of required information and used scikit-learn to search the cosine simililarities between the searched movie and the rest of the movies and export them in a pickle file and used the data from the pickle file to show on the webpage with the help of streamlit library for the overall designing of the webpage and used the tmdb api for the movie posters and hosted the website on the heroku as an web app.
