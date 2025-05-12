# City Recommendation System

This project builds a data-driven recommendation tool to help recent college graduates identify U.S. cities that align with their lifestyle preferences. The system is based on unstructured Reddit data, allowing users to go beyond standard cost-of-living metrics and uncover which cities "feel" similar to one another.

## Project Overview
- **Goal:** Recommend cities based on user input (e.g., preferred lifestyle, vibe, or target city) using natural language from Reddit discussions.
- **Data Source:** Reddit city subreddits (e.g., r/nyc, r/austin) scraped and processed into embeddings.
- **Approach:**  
  - Collected Reddit posts across multiple city subreddits.
  - Used sentence-transformer embeddings to capture text similarity.
  - Computed cosine similarity to match user-input cities to similar alternatives.
  - Created a user-facing recommendation function and plotted results using PCA for interpretability.

## Tools & Techniques
- **Python**: `pandas`, `scikit-learn`, `sentence-transformers`, `matplotlib`
- **NLP**: Sentence embeddings, cosine similarity
- **Visualization**: PCA plots for similarity mapping

## Files
- `city_recommender.ipynb`: Full notebook containing data prep, modeling, and final city recommendation logic.
- `slides.pdf`: Slide deck summarizing the project approach, key findings, and visuals.

## Key Takeaways
- Demonstrated how unstructured data (Reddit posts) can be leveraged for lifestyle-based recommendations.
- Built an explainable, lightweight tool to support more personalized relocation decisions.
- Applied NLP and similarity metrics to an unconventional dataset to solve a real-world problem.
