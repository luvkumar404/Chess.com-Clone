# Chess.com-Clone
# Chess.com-Clone

Overview:-
This project is a real-time multiplayer chess web app inspired by Chess.com, built with:

chess.js for chess logic and move validation

socket.io for real-time communication between players

Express.js as the backend server framework

EJS templating engine for rendering dynamic HTML views

It allows two players to play chess online with real-time move synchronization and game state updates.

Features:-
Real-time two-player chess game using WebSockets

Full chess rules and move validation via chess.js

Dynamic UI rendered using EJS templates

Game state and move updates pushed instantly with socket.io

Check, checkmate, stalemate, and draw detection

Room-based multiplayer support (multiple games simultaneously)

Technologies Used:-
chess.js — chess engine logic

socket.io — real-time bidirectional event-based communication

Express.js — web server framework

EJS — embedded JavaScript templating for HTML views

Node.js runtime

Installation:-
Clone the repository:- 
git clone https://github.com/luvkumar404/Chess.com-Clone.git
cd Chess.com-Clone
npm install

Start the server with nodemon for automatic reload on changes:-
nodemon app.js

Open your browser and go to:- 
http://localhost:3000
