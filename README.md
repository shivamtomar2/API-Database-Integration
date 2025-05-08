# User Management API

## Tech Stack
- FastAPI
- PostgreSQL
- SQLAlchemy
- JWT Authentication
- Bcrypt
- Pydantic

## How to Run

1. Clone the repository or extract the ZIP.
2. Set up a PostgreSQL database and update the `.env` file accordingly.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   uvicorn app.main:app --reload
   ```

## API Endpoints

- `POST /register`: Register a new user.
- `POST /login`: Login and get JWT token.
- `GET /profile/{id}`: Get user profile.
- `PUT /profile/{id}`: Update user profile.
