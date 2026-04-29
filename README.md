# Item Manager Lab Test

This project uses **Option 01**: a single Git repository containing both the frontend and backend.

## Repository Structure

```text
.
|-- backend/
|-- frontend/
|-- .gitignore
`-- README.md
```

## Frontend

- Location: `frontend/`
- Stack: React + Vite
- Start locally:
  ```bash
  cd frontend
  npm install
  npm run dev
  ```

## Backend

- Location: `backend/`
- Stack: Node.js + Express + MongoDB
- Start locally:
  ```bash
  cd backend
  npm install
  npm run dev
  ```

## Environment Variables

- Frontend uses `frontend/.env`
- Backend uses `backend/.env`

Example frontend variable:

```env
VITE_API_URL=http://localhost:5000/api
```

Example backend variables:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

## Local Testing

1. Start the backend on port `5000`
2. Start the frontend on port `5173`
3. Open `http://localhost:5173`
4. Verify creating, editing, listing, and deleting items
