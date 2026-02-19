# QuestForge ![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![Version](https://img.shields.io/badge/version-1.0.0-blue)

## Project Description
QuestForge is a web application that allows players to create, share, and embark on custom quests in their favorite games. Utilizing AI and advanced data storage, players can generate quests tailored to their interests and collaborate with friends to enhance their gaming experience.

## Features
- 🎮 Dynamic quest generation based on player preferences
- 🤝 Real-time collaboration for multiplayer quest creation
- 🗣️ Integration with AI-driven NPC dialogue systems

## Tech Stack
### Frontend
- React.js

### Backend
- FastAPI
- Langchain

### Database
- QdrantDB
- Pinecone

## Installation
To set up QuestForge locally, follow these steps:

- Clone the repository
bash
git clone https://github.com/vikasexcel/questforge
- Navigate to the project directory
bash
cd questforge
- Install the required dependencies for the backend
bash
pip install -r requirements.txt
- Install the required dependencies for the frontend
bash
cd frontend
npm install
- Start the backend server
bash
uvicorn main:app --reload
- Start the frontend development server
bash
npm start
## Usage
Once the application is running, navigate to `http://localhost:3000` in your web browser to access QuestForge. You can create quests, collaborate with friends, and explore AI-driven NPC dialogues.

## API Documentation
For detailed API documentation, please refer to the [API Documentation](https://github.com/vikasexcel/questforge/wiki/API-Documentation).

## Testing
To run the tests for QuestForge, follow these steps:

- Navigate to the backend directory
bash
cd backend
- Run the tests
bash
pytest
## Deployment
For deploying QuestForge, you can use platforms like Heroku, AWS, or DigitalOcean. Ensure that you set up environment variables and database connections as per your deployment platform's requirements.

## Contributing
We welcome contributions to QuestForge! Please follow these guidelines:

- Fork the repository
- Create a new branch for your feature or bug fix
- Make your changes and commit them
- Push your branch to your forked repository
- Create a pull request detailing your changes

Thank you for your interest in contributing to QuestForge! Happy questing! 🚀