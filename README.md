# Blackjack Game

## About This Project

Welcome to the Blackjack Game! This is a simple web-based Blackjack game that's fun to play and easy to get started with. It's built with React for the frontend and Node.js/Express for the backend, and it uses MongoDB to keep track of the game state and player data. Enjoy real-time updates and a responsive design that works great on all devices. Play a round, see who wins, and have fun!

## Features

- **Interactive Gameplay**: Start a game, hit to get more cards, and stand when you're done.
- **Real-time Updates**: The game state updates instantly as you play.
- **Winner Announcement**: See who wins at the end of each game.
- **Responsive Design**: Looks good on any device.

## Technologies Used

- **Frontend**: React
- **Backend**: Node.js and Express
- **Database**: MongoDB

## Installation and Setup

1. **Clone the repo**:
   ```sh
   git clone https://github.com/your-username/blackjack-game.git
   cd blackjack-game
   ```

2. **Install the dependencies**:
   * For the backend:
     ```sh
     cd blackjack-server
     npm install
     ```
   * For the frontend:
     ```sh
     cd ../blackjack-client
     npm install
     ```

3. **Set up environment variables**:
   * Create a `.env` file in the `blackjack-server` directory.
   * Add the following:
     ```
     MONGO_URI=your-mongodb-uri
     NODE_ENV=development
     PORT=5000
     ```

4. **Build and start the app**:
   * Build the frontend and install backend dependencies:
     ```sh
     cd blackjack-client && npm run build && cd ../blackjack-server && npm install
     ```
   * Start the backend server:
     ```sh
     npm start
     ```

5. **Play the game**:
   * Open your web browser and go to `http://localhost:5000`.

Enjoy playing Blackjack!
```

