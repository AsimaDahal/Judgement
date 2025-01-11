# Judgement

Card game (Popular Variation of Spade)

Judgment is a trick-taking card game where players predict the number of tricks they will win in each round. Accurate predictions earn points, while incorrect ones result in penalties. The game involves strategic bidding, card play, and scoring, making it engaging and competitive.

High-Level Architecture (Monolithic)

- Client-Server Model: The application follows a client-server architecture.
- - Front-End: Built with React, responsible for the user interface and handling user interactions.
- - Back-End: Developed with Spring Boot, handling game logic, data management, and providing WebSocket endpoints.

- Communication:
- - WebSockets: For real-time communication during gameplay.
- - RESTful APIs: For authentication, game setup, and other non-real-time interactions.

- Database: MongoDB
