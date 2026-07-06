 AI-RECOMMENDATION-LOGIC
 AI Recommendation Logic
'''A beginner-friendly AI project that builds a simple content-based recommendation system. It takes a user's interests as text input, matches them against a catalog of items using TF-IDF vectorization and Cosine Similarity, and displays the top matching recommendations.'''

## How It Works (Input → Process → Output)
User types their interests (e.g. "python and machine learning")
TF-IDF converts text into weighted numerical vectors, then Cosine Similarity measures how closely the user's interests align with each item's description
Displays the Top-N best matching items with their similarity scores

 Tech Used
Python, scikit-learn (TfidfVectorizer, cosine_similarity)
