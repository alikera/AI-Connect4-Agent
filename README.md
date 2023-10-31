# Connect4 AI with Minimax Algorithm

Welcome to Connect4 AI, a challenging project designed to test your skills against a powerful AI opponent in the classic game of Connect 4. This implementation utilizes the Minimax algorithm, enhancing the game with strategic intelligence.

## Goal

The goal of this project is to predict the opponent's moves using the Minimax algorithm, aiming to secure a victory in the game of Connect 4.

## Phases of Development

This project consists of two essential phases, each demonstrating a different Minimax strategy:

### Phase 1: Minimax with Pruning
In the first phase, the AI employs the Minimax algorithm with pruning techniques. Pruning optimizes the search space, enhancing efficiency without compromising accuracy.

### Phase 2: Minimax without Pruning
The second phase focuses on Minimax without pruning, allowing for an exhaustive exploration of all possible moves, providing a deeper analysis of the game state. 

## Description

In Connect 4, players take turns choosing a column to drop their pieces. The piece falls down the chosen column until it either lands on another piece or reaches the bottom row. The Minimax algorithm is employed here to provide precise predictions of the opponent's moves. The depth parameter controls the algorithm's accuracy; a higher depth improves precision but also increases time complexity and victory chances.

## Heuristic Function

A meticulously designed heuristic function evaluates the best possible moves. It prioritizes positions that lead to winning states, such as placing a piece next to an existing row of three marbles. Additionally, the function focuses on preventing the opponent from winning by blocking their potential winning moves. By assigning values to each cell on the board, this optimized and consistent heuristic ensures strategic decision-making.


## Verification and Accuracy

To ensure the accuracy of the algorithm, various instances of the game table were evaluated. These evaluations were performed to validate the AI's performance, ensuring both efficiency and accuracy in different gameplay scenarios.

## Usage

To experience the Connect4 AI, instantiate the `ConnectSin` class, set the desired maximum depth for the Minimax algorithm, and choose whether to enable pruning for reduced time complexity. The AI can be played against a human opponent, offering a challenging and engaging gameplay experience.

Feel free to explore, contribute, and enhance the Connect4 AI project. Enjoy the thrill of playing against an intelligent opponent and sharpen your Connect 4 skills!
