
# Recommender Systems From Scratch

This repository implements foundational and intermediate recommender system models **entirely from scratch**,
without relying on external recommender libraries such as Surprise or implicit.
The goal is to build a deep, hands-on understanding of how core recommendation algorithms work under the hood.

---

## Project Structure

- `notebooks/`
  - **RS_Chapter1_Foundations.ipynb**  
    Exploratory data analysis and regression-based prediction models.
  - **RS_Chapter2_Collaborative_Filtering.ipynb**  
    User-based and item-based collaborative filtering implementations.
  - **RS_Chapter3_Content_Based.ipynb**  
    Personalized and non-personalized content-based recommendation models.

- `src/`
  - Helper functions such as KNN-based similarity search and evaluation metrics.

- `data/`
  - Joke ratings, text datasets, and stopword lists used for building models.

---

## Setup Instructions

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/wins-wang/recommender-systems-from-scratch.git
cd recommender-systems-from-scratch
pip install -r requirements.txt
```

---

## Covered Topics

### Chapter 1: Foundations
- Exploratory Data Analysis (EDA) and visualization
- Simple and Ridge Regression for rating prediction
- Popularity-based baseline recommender

### Chapter 2: Collaborative Filtering
- User-User similarity computation (Pearson correlation)
- Item-Item similarity computation (Cosine similarity)
- K-Nearest Neighbors (KNN) prediction for rating estimation
- Top-N recommendations based on collaborative filtering
- Evaluation using RMSE, MAE

### Chapter 3: Content-Based Recommendation
- Text preprocessing (tokenization, stopword removal, stemming)
- TF-IDF feature construction for jokes
- Personalized user profiling based on liked items
- Non-personalized item similarity recommendation
- Evaluation using Precision@k, Recall@k and metric visualization

---

## Future Improvements

- Model hyperparameter optimization (e.g., dynamic k-tuning)
- Incorporating additional user/item features
- Scaling to larger datasets (e.g., MovieLens)
- Exploring hybrid recommendation approaches

---

## License

This project is licensed under the MIT License.  
Feel free to fork, adapt, and build upon this work!

---

## Acknowledgements

- Course assignments inspiration from RS/ML academic settings.
- NLTK and scikit-learn used for basic text preprocessing and TF-IDF vectorization.
