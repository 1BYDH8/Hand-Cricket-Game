# Hand Cricket Game in Java

## Description

The Hand Cricket Game is a digital simulation of the popular hand cricket played among children, designed in Java. In this game, you face off against a computer, where both players take turns acting as either the batsman or bowler. The game is simple yet offers a fun and engaging experience, requiring strategic hand choices to outsmart your opponent.

## Features

- **Player vs Computer**: You compete against an AI opponent.
- **Batsman and Bowler Modes**: Both batting and bowling are included in the game.
- **Random AI Behavior**: The computer's moves are random, simulating a real-life experience.
- **Game Modes**: Choose to bat or bowl first.
- **Score Tracking**: The game tracks runs, wickets, and overs.
- **Victory Conditions**: Game ends when wickets fall or a target is chased.

## Prerequisites

- Java Runtime Environment (JRE)
- Java Development Kit (JDK) for compiling the code

## How to Run the Game

1. **Clone the Repository**:
```bash
git clone https://github.com/1BYDH8/Hand-Cricket-Game.git
```

2. **Navigate to the Project Directory:**
```bash
cd Hand-Cricket-Game
```

3. **Compile the Java Files:**
``` bash
javac main.java
```

4. **Run the Game:**
```bash
java main
```

## **How to Play**

1. Choose to Bat or Bowl: You decide if you want to bat or bowl first.
2. Batsman Mode:
- The player chooses a number (1-6) representing their hand gesture.
- The computer randomly picks a number.
- If the numbers match, the player loses a wicket.
- If they don't match, the player's score increases by the number they chose.
3. Bowler Mode:
- The player chooses a number to bowl.
- The computer randomly picks a number.
- If the numbers match, the computer loses a wicket.
- If they don't match, the computer's score increases.
4. Victory:
- The game ends when all wickets are lost or when the target is chased.

**Example Gameplay**
```yaml
Choose Bat or Bowl:
1. Bat
2. Bowl

Your Turn to Bat:
Choose a number (1-6): 4
Computer chose: 2
Runs scored: 4

Choose a number (1-6): 5
Computer chose: 5
You're out! Wickets remaining: 1
```

## **Contribution**
Feel free to fork the repository, submit issues, or contribute to enhance the game.