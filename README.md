# Movie_Recommender_System
Built a movie recommender system with Streamlit 
In this project I have built a content based movie recommender system. The algorithm recommends products that are similar to the ones that a user has liked in the past. This similarity (generally cosine similarity) is computed from the data we have about the items as well as the user’s past preferences.

What it does:
![movie](https://github.com/user-attachments/assets/d35fd9e6-c468-432a-8c1d-fe62e6711d99)

Live Demo


https://github.com/user-attachments/assets/0d52850a-ffb1-4791-a0e4-0a2e14eeb6f3

How it does:
Content Based Filtering - They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.

How to get the API key for images?
Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.

![mrs](https://github.com/user-attachments/assets/fb352d69-99b6-42f1-8ade-ee1d47dcc400)

Similarity Score :
How does it decide which item is most similar to the item user likes? Here we use the similarity scores.
It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
![mrs1](https://github.com/user-attachments/assets/9984d901-6a37-4999-81fc-81309418c6a4)

How Cosine Similarity works?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

![mrs3](https://github.com/user-attachments/assets/dfd0722f-79c6-4d0c-b044-eb5c91f7644e)


Sources of the datasets :
I have used the TMDB 5000 movies dataset to build the model

You can collect dataset from https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata





