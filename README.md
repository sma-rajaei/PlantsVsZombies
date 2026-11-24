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

This game uses a client-server architecture to manage multiplayer communication.
Players connect to the local server by entering the server IP address and port number:
**IP : 127.0.0.1
Port : 12345**

<img width="1512" height="802" alt="Start Connection Page" src="https://github.com/user-attachments/assets/b320cc2c-f22a-4aa5-936d-9c0c6f7f9c55" />

-------

## User Authentication System

### Players can:

### Create A New Account:

<img width="1217" height="774" alt="Signup Page" src="https://github.com/user-attachments/assets/684b6cbe-ea7b-442e-86c4-8ecc114291f3" />

### Login To An Existing Account:
  
<img width="1514" height="784" alt="Authorization Page" src="https://github.com/user-attachments/assets/8d3a232b-874c-4b10-8766-18912b7ceead" />

### Recover Forgotten passwords Using Their Registered Phone number:

<img width="1489" height="805" alt="image" src="https://github.com/user-attachments/assets/aa14b545-5200-4e7c-8664-36d71f333346" />


-------

## Main Menu

<img width="1241" height="791" alt="Main Menu" src="https://github.com/user-attachments/assets/13ed8525-0b63-4fb7-b1b0-8860e0e910ba" />

### Play

**Multiplayer Matchmaking :** By clicking this button, players can start a multiplayer match by sending a game request to the other player connected to the server.
If opponent accepts the requesst, the multiplayer game starts.

<img width="393" height="321" alt="Match Invitation" src="https://github.com/user-attachments/assets/ed09161b-7871-4b67-b1f6-a6e7159a9e17" />


### Change Account Information

<img width="1178" height="784" alt="Change Account Information" src="https://github.com/user-attachments/assets/e9ae65e7-4f07-450c-97ff-dbc128df3743" />


### View Match History (Wins & Losses)

### Log Out From The Account (Return To The Authentication Page) 


# Gameplay

## Plants' Side:

<img width="969" height="585" alt="Plant Side Gameplay" src="https://github.com/user-attachments/assets/e7bdc5c2-f03f-438b-9ce2-441636185344" />

## Zombies' Side:

<img width="965" height="578" alt="Zombie Side Gameplay" src="https://github.com/user-attachments/assets/6a2c04da-c46e-4d07-97a9-8d5854f7954e" />

## Match System

- Each match consists of 2 or 3 rounds
- Players compete until one player achieves **2 Won Rounds**
- Player roles are swapped between rounds to provide a fair gameplay experience

## Game Mechanics

The gameplay includes several elements inspired by Plants vs. Zombies, including:

- Animated graphical elements
- Custom-designed game rules
- Resource and loot management system
- Strategic gameplay mechanics
- Real-time player interactions

## Emotion and Communication System

To improve communication between players during gameplay, an emotion system was implemented.
Players can send any one of the four available emojis to their opponent during the match.



# Technologies Used

- **Programming Language:** C++
- **Framework:** Qt
- **Database:** Local Database Storage
- **Architecture:** Client-Server Model

# Course Information

**Course:** Advanced Programming  
**University:** Isfahan University of Technology

**Lecturer:**  Ali Iranidoost

**Teaching Assistants:**
Mahrokh Mousavi,  Saba Rafiei

# Acknowledgements

*The project also has a windows installer that did'nt uploaded on github.
Size After Installation : ~ 156 MB
