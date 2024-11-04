# Racquetball Game Simulator

A Python program that simulates racquetball games between two players with different skill levels, implementing both traditional and fair-play serving rules.

## Features

- Two serving rule implementations:
  - Traditional Rule: Server maintains serve until losing a point
  - Fair-Play Rule: Alternating serves after each point
- Probability-based gameplay simulation
- Multiple game simulations with statistical analysis
- Input validation for player probabilities
- Detailed game statistics and win rates

## Flowchart
![Racquetball Game Flowchart](Images/Flowchart.jpg)

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/racquetball-simulator.git

# Navigate to project directory
cd racquetball-simulator

# Run the program
python racquetball_game.py
```

## Usage

1. Run the program
2. Enter probability of Player A winning serve (0-1)
3. Enter probability of Player B winning serve (0-1)
4. Enter number of games to simulate
5. View simulation results

Example input:
```
What is the prob. player A wins a serve? 0.6
What is the prob. player B wins a serve? 0.5
How many games to simulate? 100
```

## Project Structure

```
racquetball-simulator/
│
├── racquetball_game.py      # Main game implementation
├── README.md                # This file
└── LICENSE                  # License file
```
