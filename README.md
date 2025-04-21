# Compass Chatbot Application

This project consists of a frontend React application and a backend Express server that together provide a financial assistant chatbot using the Gemini API.

## Prerequisites

- Node.js (v16 or later recommended)
- npm or yarn
- Gemini API key (set as environment variable)

## Setup

### Backend

1. Navigate to the backend directory:

```bash
cd compass-backend
```

2. Create a `.env` file with your Gemini API key:

```
GEMINI_API_KEY=your_gemini_api_key_here
PORT=4000
```

3. Install dependencies:

```bash
npm install
```

4. Start the backend server:

```bash
node server.js
```

The backend server will run on `http://localhost:4000`.

### Frontend

1. Navigate to the frontend directory:

```bash
cd compass-frontend
```

2. Install dependencies:

```bash
npm install
```

3. Start the frontend development server:

```bash
npm run dev
```

The frontend will run on `http://localhost:3000` (or as indicated by Vite).

## Usage

- Open the frontend URL in your browser.
- Login with the test user credentials:
  - Username: `testuser`
  - Password: `password`
- Use the chatbot floating button on the dashboard to interact with the Gemini-powered chatbot.
- Upload bank statements and explore other features.

## Notes

- The backend uses in-memory storage for demo purposes; data will reset on server restart.
- Ensure the Gemini API key is valid and has sufficient quota.
- CORS is enabled on the backend to allow frontend requests.

## Troubleshooting

- If chatbot responses fail, check backend console for Gemini API errors.
- Verify the GEMINI_API_KEY environment variable is set correctly.
- Ensure backend and frontend servers are running.

## License

This project is provided as-is for demonstration purposes.
