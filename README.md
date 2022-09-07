# Quran Similary Score Jupyter Notebooks

The attached jupyter notebooks show the methodology used to find similar verses in the Qur'an based on their Arabic root words. 

The notebooks tokenize, vectorize and lemmatize the verses. Then apply cosine similarity algorithm on the resultant space to find most similar vectors - which are then ranked between 0 to 1.

The results are compiled in a Pandas DataFrame, saved to a pickle file, and uploaded into a relational database. This database is ultimately used for the API (https://github.com/jawadshuaib/quran-similarity-search-api) and application (https://github.com/jawadshuaib/quran-similarity-search).


Note: The pickle file used to import the initial data structure was not uploaded on GitHub due to its enormous size. But it can be created manually as it just a permutational combination of all verses in the Qur'an.
