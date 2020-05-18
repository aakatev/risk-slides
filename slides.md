---
marp: true
theme: uncover
---

<!-- theme: uncover -->

# Risk Game 667

Artem Akatev

Ryan Shu

Ricardo Colin

Mohammad Ashan

---

## Outline

- Overview

- Specifications

- Technology Used

- Components

- Demo

---


## Overview

##### Based on risk board game

- 42 territories

- Conquer all 42 to win

- Roll dice to determine winner 

---

## Simplifications

- Only 2 players

- No army separation (Infantry, cavalry, etc)

- No cards

---

## Functional Specs

- Authentication

- Live chat

- Live lobby

- Live gaming experience

---

## Non functional specs

- Fully functional on Chrome 81+

- Look nice on non-mobile devices

- Deployed on Heroku

- Using Postgres to store data

---

## Technology Used

- Server: JS and Express

- Client: JS and Preact/Vue

- Storage: Postgres

- Tons of dependencies

---


## Components

- Database

- Server

- Lobby

- Chat

- Gameboard

---

## Database

#### Stores:

- Users

- Messages

- Games

- State of each game

---

## Server

#### Key functions

- Process game state, and chat messages

- Manages sessions

- Broadcasts events (WS)

- Exposes HTTP API

---

## Lobby, Chat, and Gameboard

#### Key functions

- Listen for events (WS)

- Execute state update logic 

- Rerender the updated state


---

## Demo

[Link](https://risk-game-667.herokuapp.com/lobby)


---

# <!--fit--> :+1:
