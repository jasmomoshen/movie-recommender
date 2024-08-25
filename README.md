# Movie Recommender

This project is a content-based movie recommendation system built using Python. It processes movie metadata and recommends similar movies based on their tags, genres, cast, and crew.

## Features

- **Data Processing**: Merges movie and credits datasets, processes genres, keywords, cast, and crew data.
- **Vectorization**: Uses `CountVectorizer` to convert text data into vectors.
- **Similarity Calculation**: Utilizes cosine similarity to find and rank movies similar to a given input.
- **Interactive Interface**: Built with Streamlit for easy user interaction.
