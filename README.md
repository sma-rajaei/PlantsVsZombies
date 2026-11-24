# Plants vs. Zombies 

A two-player multiplayer strategy game inspired by **Plants vs. Zombies**, developed in **C++ using Qt Framework** as the final project for the Advanced Programming course at Isfahan University of Technology.

The project includes a complete client-server architecture, user authentication system, local database management, multiplayer gameplay, animations, resource management, and real-time player interaction features.

-------

## Overview

This project is a multiplayer game where two players can create accounts, log in, challenge each other, and compete in a turn-based battle inspired by the gameplay mechanics of Plants vs. Zombies.

The game provides a complete user experience, from account creation and authentication to multiplayer matchmaking and gameplay.

-------

# Features

## Client-Server Connection

- Players connect to the game by entering the server IP address and port number.
- The game uses a client-server architecture to manage multiplayer communication.

<img width="1512" height="802" alt="Start Connection Page" src="https://github.com/user-attachments/assets/b320cc2c-f22a-4aa5-936d-9c0c6f7f9c55" />

-------

## User Authentication System

### Players can: ###

### Create a new account: ###

<img width="1217" height="774" alt="Signup Page" src="https://github.com/user-attachments/assets/684b6cbe-ea7b-442e-86c4-8ecc114291f3" />

### Log in using an existing account: ###
  
<img width="1514" height="784" alt="Authorization Page" src="https://github.com/user-attachments/assets/8d3a232b-874c-4b10-8766-18912b7ceead" />

### Recover forgotten passwords using their registered phone number: ###

<img width="1489" height="805" alt="image" src="https://github.com/user-attachments/assets/aa14b545-5200-4e7c-8664-36d71f333346" />


- Update their accounts' information.

-------

## Main Menu

After logging in, players can access:

- Start a multiplayer game.
- Send a game request to another player.
- View account information.
- Update profile details.
- View match history, including wins and losses.
- Log out from the account.

-------

## Multiplayer Matchmaking

- A player can send a game request to another player.
- The opponent can accept or reject the request.
- After acceptance, the multiplayer game starts.

-------

# Gameplay

## Match System

- Each match consists of multiple rounds.
- Players compete until one player achieves **two round victories**.
- Player roles are swapped between rounds to provide a fair gameplay experience.

-------

## Game Mechanics

The gameplay includes several elements inspired by Plants vs. Zombies, including:

- Custom-designed game rules.
- Animated graphical elements.
- Resource and loot management system.
- Strategic gameplay mechanics.
- Real-time player interactions.

-------

## Emotion System

To improve communication between players during gameplay, an emotion system was implemented.

Players can send one of four available emojis/emotes to their opponent during the match.

-------

# Technologies Used

- **Programming Language:** C++
- **Framework:** Qt
- **Database:** Local Database Storage
- **Architecture:** Client-Server Model

-------

# Course Information

**Course:** Advanced Programming  
**University:** Isfahan University of Technology

**Professor:**  
- Ali Iranidoost

**Teaching Assistants:**
- Mahrokh Mousavi
- Saba Rafiei

-------
All have been added to the repository collaborators section.

-------

# Acknowledgements

Special thanks to the course professor and teaching assistants for their guidance and support throughout the development of this project.

*The project also has windows installer that did'nt uploaded on github.
