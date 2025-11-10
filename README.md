Vibe Matcher

Vibe Matcher is an AI-powered fashion recommendation prototype built to understand vibes, not just words. Developed as part of Nexora’s initiative to explore emotional intelligence in AI, this project transforms natural language queries like “urban minimal chic” or “cozy winter streetwear” into meaningful product matches.

Unlike traditional search systems that rely on keyword matching, Vibe Matcher uses semantic embeddings to represent both product descriptions and user vibes as high-dimensional vectors. It then computes cosine similarity to retrieve the top-3 products that best align with the user’s mood or aesthetic intent.



🧩 Tech Stack

Language: Python 3.10+

Libraries: pandas, numpy, scikit-learn, sentence-transformers

Model: thenlper/gte-large (from Hugging Face)

Data Format: CSV / Parquet
