# Data Flow

1. User interacts with frontend (React)

2. Frontend sends request to backend (Node.js)

3. Backend processes the request:
   - Authentication (login/register)
   - Fetch products
   - Manage cart

4. Backend communicates with database (MongoDB)

5. Database returns data to backend

6. Backend sends response to frontend

7. Frontend displays data to user

## Recommendation Flow

1. Backend sends user data to ML model (Python)

2. ML model generates product recommendations

3. Backend receives recommendations

4. Backend sends recommendations to frontend
