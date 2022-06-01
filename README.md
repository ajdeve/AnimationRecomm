# AnimationRecomm
Animation Recommendation utilizing content-based, collaborative-filtering and rating prediction. 

## Team
Ahjeong Yeom, Kenji Laurens, Pengfei Gu, Zongyuan Yu

## Project Summary
Problem Statement: Create a recommendation engine for animation consumers given a comprehensive animation dataset with users’ ratings and interactions with animations, using collaborative and content-based recommendation engines. Thorough ML and DL-based approaches to EDA, feature extraction and modelling will help improve recommendations for the users and enhance their viewing experience. Solid animation recommendation engine will help animation streaming services (ie. Netflix, HULU etc) to provide more targeted and improved recommendations on animations and thus generate more revenue from increased user engagement and satisfaction. 

## Data 
**Source:**  https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020?select=rating_complete.csv​
**Dataset Profile:** This dataset contains 57 Million ratings applied to 16872 animes by 310.059 users.​
- anime.csv
- anime_with_synopsis.csv
- animelist.csv
- rating_complete.csv
- watching_status.csv

## Implementation Tools
- Python
- SpaCy
**Visualization**
- Matplotlib
- Wordcloud
- Plotly

## Models
1. Content Based Model (SpaCy NLP pipeline to clean data, Count Vectorizor and Cosine Similarity)
2. Collaborative Filtering Model
3. Keras (Dot Product & CNN Model) 

## Project Folder Structure
### Models
- Content-based (Synopsis) 
- Collaborative-filtering (User-based and item-based)
- Rating Prediction Powered by Deep Learing

