# Movie-Recommendation-System
Movie recommendation using cosine similarity

Movie recommendation utilizes cosine similarity. The features are combined into a single string and converted into feature vectors using TfidfVectorizer. Cosine similarity is then calculated between all movie pairs, and the user is prompted to input their favorite movie. Then it finds the closest match to the user's input, retrieves similarity scores for the selected movie, sorts them, and suggests the top 30 most similar movies based on cosine similarity.
