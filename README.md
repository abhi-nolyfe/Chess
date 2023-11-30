# Online Multiplayer Chess Game (In Progress)

## Overview
This project aims to create a web-based multiplayer chess game utilizing Django Channels and Redis for the backend and React for the frontend. The game will support real-time gameplay between multiple users, possibly incorporating a chat feature for interaction. 

### Features
- **Multiplayer Gameplay:** Allows multiple users to play chess together in real-time.
- **Turn Rotation:** Unique feature enabling multiple players to control a single side (e.g., multiple players controlling the white pieces, taking turns on each move).

## File Structure
- **Client:** Houses the React frontend code.
- **Server:** Contains the Django backend files utilizing Django Channels and Redis for handling real-time communication.

## Setup
1. **Backend (Django Channels)**
   - Install the required dependencies.
   - Set up Django Channels and Redis configurations.
   - Implement the chess game logic within the Django backend.

2. **Frontend (React)**
   - Set up React components for the chess game interface.
   - Integrate real-time communication with the Django Channels backend.

3. **Running the Application**
   - Start the Django server and ensure Redis is running.
   - Launch the React frontend to enable gameplay through the browser.

## Future Improvements
- **Chat Feature:** Incorporate a chat system for players to communicate during gameplay.
- **Enhanced Gameplay Options:** Expand gameplay features and options to enrich the gaming experience.

## Contributing
Feel free to fork the repository, make improvements, and create pull requests. Contributions are welcome!
