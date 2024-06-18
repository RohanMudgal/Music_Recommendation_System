# Music_Recommendation_System
## Spotify Playlist Analyzer and Recommendation Engine

This project explores the world of music data using Spotify's API and popular data science techniques. 

**Project Goals:**

* Utilize Spotify's API to retrieve music data from a trending playlist.
* Create a pandas DataFrame to organize and analyze the retrieved music information.
* Implement content-based filtering using cosine similarity on audio features to recommend similar songs.
* Develop a hybrid recommendation system that combines content-based recommendations with weighted popularity scores based on release date.

**Implementation:**

* The script first establishes a connection with Spotify's API using OAuth authentication.
* It retrieves music data from a chosen Spotify playlist, including details like artist names, song titles, and audio features.
* The script then utilizes pandas to create a structured DataFrame for efficient data manipulation and analysis.
* To enable content-based recommendations, music features are normalized using Min-Max scaling. Cosine similarity is applied to calculate the similarity between songs based on their audio features.
* A hybrid recommendation system is implemented that merges content-based recommendations with a weighted popularity score based on a song's release date. This aims to balance finding songs with similar musical characteristics while incorporating the factor of a song's current popularity.

**Conclusion:**

This project demonstrates how to leverage Spotify's API and data science techniques to explore and analyze music data.  It showcases methods for creating content-based recommendations and introduces the concept of hybrid recommendation systems that combine various factors. As an ongoing project, it can be further extended by:

* Incorporating user data and listening history to personalize recommendations.
* Exploring additional music features and attributes for a more comprehensive analysis.
* Building a user interface to allow users to interact with the recommendations.


**Note:**

The provided code snippet showcases the core functionalities of the project. A complete implementation might include additional functionalities for error handling, data cleaning, and user input.
