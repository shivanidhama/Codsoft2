# AI Projects

This repository contains three beginner-friendly Artificial Intelligence projects developed using Python. Each project focuses on a different AI concept, including Natural Language Processing, Game AI, and Computer Vision.

## Projects Included

1. Chatbot with Rule-Based Responses
2. Tic-Tac-Toe AI
3. Face Detection and Recognition

---

# 1. Chatbot with Rule-Based Responses

## Description

The Rule-Based Chatbot is a simple chatbot that responds to user messages using predefined rules and `if-else` statements.

The chatbot checks the user's input for specific words or phrases and provides an appropriate predefined response.

## Features

* Simple graphical user interface
* Rule-based responses
* Keyword matching
* Interactive chat window
* Clear chat option
* No external AI model required

## Technologies Used

* Python
* Tkinter
* If-Else Statements
* Basic Natural Language Processing

## How It Works

```text
User enters message
        ↓
Input is converted to lowercase
        ↓
Predefined rules are checked
        ↓
Matching keyword is identified
        ↓
Response is generated
        ↓
Response is displayed in GUI
```

## Example

```text
You: Hello

Bot: Hello! How can I help you?

You: What is your name?

Bot: My name is Simple AI Chatbot.
```

## Run the Project

```bash
python chatbot.py
```

---

# 2. Tic-Tac-Toe AI

## Description

Tic-Tac-Toe AI is a game in which a human player plays against an AI opponent.

The AI uses the **Minimax algorithm** to evaluate possible moves and select the best move. Alpha-Beta Pruning can also be used to improve the efficiency of the search.

## Features

* Graphical user interface
* Human vs AI gameplay
* AI opponent
* Minimax algorithm
* Alpha-Beta Pruning
* Win and draw detection
* New Game option

## Technologies Used

* Python
* Tkinter
* Minimax Algorithm
* Alpha-Beta Pruning
* Game Theory

## How It Works

```text
Human Player
     ↓
Selects a position
     ↓
Game Board Updated
     ↓
AI evaluates possible moves
     ↓
Minimax selects the best move
     ↓
AI makes its move
     ↓
Winner / Draw is checked
```

## Game Symbols

```text
Human → X
AI    → O
```

## Example Board

```text
 X | O | X
---+---+---
 O | X | 
---+---+---
   | O | X
```

## Run the Project

```bash
python tic_tac_toe.py
```

## Learning Outcomes

* Understand game-playing AI
* Learn Minimax
* Understand search algorithms
* Learn decision-making in AI
* Understand Alpha-Beta Pruning

---

# 3. Face Detection and Recognition

## Description

The Face Detection and Recognition project demonstrates how computer vision can be used to detect faces in images or video.

Face detection identifies the location of faces, while face recognition attempts to identify a detected face by comparin
