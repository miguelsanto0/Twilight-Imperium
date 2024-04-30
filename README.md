# Twilight-Imperium
This repository contains the backend system for the Twilight Imperium game, designed to handle multiplayer game sessions via a simple HTTP server. The backend facilitates game creation, state management, player movements, and real-time updates, providing a robust framework for a seamless gaming experience.

Architecture
Server: Sets up an HTTP server that listens to various endpoints to handle game logic and player interactions. It supports operations such as player login, game creation, and fetching game state.
Client: Handles user interactions and sends requests to the server based on player actions.
Game: Manages game logic, including state updates and player actions.
Main: Entry point of the backend, initializes the server and starts the game service.
Pair: Utility class to manage data structures involving pairs of values.
Handlers: Dedicated classes for handling specific types of requests, such as login requests, game creation, and move operations.
