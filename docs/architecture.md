# Data Flow

1. User interacts with frontend (HTML/CSS/JS)

2. Frontend sends request to backend (Flask API)

3. Backend processes request:

   - /api/upload:
     Stores resource in database

   - /api/recommend:
     Uses ML model (TF-IDF + cosine similarity)

   - /api/ask:
     Returns AI-based response

   - /api/youtube:
     Returns video links

4. Database (SQLite) stores resources

5. ML model generates recommendations

6. Backend sends response to frontend

7. Frontend displays results
