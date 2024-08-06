# Chatbot Ollama Project

This project is a chatbot application based on Ollama. The frontend is developed with React and Vite, while the backend uses the Hono framework running on Node.js.

## Project Structure

The project consists of two main parts:

1. Backend (Hono + Node.js)
2. Frontend (React + Vite)

### Backend

The backend is developed using the Hono framework and includes the following features:

- Ollama integration
- CORS settings
- Message history management
- REST API endpoints

### Frontend

The frontend is developed using React and Vite and includes the following features:

- Chat interface
- Theme switching (light/dark)
- Multi-language support (using i18next)
- API requests with Axios

## Requirements

- Node.js (v14 or higher)
- npm (v6 or higher)

## Installation

1. Clone the repository:
git clone https://github.com/erenasiroglu/chatbot-ollama.git
cd chatbot-ollama
2. Backend setup:
   
cd backend
npm install

4. Frontend setup:
cd ../frontend
npm install
   
## Running the Application

1. Start the backend:
cd backend
npm run dev

The backend will run using `tsx watch` and automatically reload on changes.

3. Start the frontend:
cd frontend
npm run dev
The frontend will run in development mode using Vite.

3. Open your browser and navigate to the address provided by Vite (usually `http://localhost:5173`) to view the application.

## Building for Production

To build the frontend project for production:
cd frontend
npm run build

The built files will be created in the `frontend/dist` directory.

## Technologies Used

### Backend
- Hono: ^4.5.3
- @hono/node-server: ^1.12.0
- ollama: ^0.5.6
- TypeScript
- tsx: ^4.7.1 (for development)

### Frontend
- React: ^18.3.1
- Vite: ^5.3.4
- TypeScript: ^5.2.2
- axios: ^1.7.3
- i18next: ^23.12.2
- react-i18next: ^15.0.0

## Features

- Turkish and English language support
- Light/dark theme option
- Chatbot integrated with Ollama
- Message history storage

## Development

This project incorporates modern web development practices:

- React hooks
- Fast development and building with Vite
- Type safety with TypeScript
- Code quality control with ESLint
- Multi-language support with i18next

## Contributing

1. Fork this repository
2. Create a new branch (`git checkout -b feature/newFeature`)
3. Commit your changes (`git commit -am 'New feature: Details'`)
4. Push your branch (`git push origin feature/newFeature`)
5. Create a new Pull Request

