# Connect4 AI

This project implements an AI agent for the classic game **Connect Four**, using reinforcement learning techniques such as **TD(λ)**. The AI can be played against through an interactive **PyGame GUI**, offering a fun and educational way to explore machine learning in games.

## Features

- **Reinforcement Learning**: Trained using Temporal Difference Learning with eligibility traces (TD(λ)).
- **Interactive Gameplay**: Play against the AI using a graphical interface built with PyGame.
- **Pre-trained Agent**: Includes a trained model (`best_agent2.npy`) for immediate gameplay.
- **Educational Notebook**: The `DSAI444_Final.ipynb` notebook walks through the training process and logic behind the AI.

## Getting Started

### Prerequisites

- Python 3.7+
- PyGame
- NumPy

Install dependencies:

```bash
pip install pygame numpy
```

### Running the Game

To run the game, comment out the line that reads in the previous weights, and the line that trains the model (both are toward the bottom of the file).

### Training the Agent (Optional)

If you'd like to retrain the agent you can input `best_agent2.npy` to use those weights as a baseline or start from scratch by commenting out that line.

You can adjust hyperparameters like learning rate, discount factor, and λ in the script.

## Author

**Parker Pratt**  
For questions or contributions, feel free to open an issue or pull request or message me through GitHub, Handshake, LinkedIn, or email.
