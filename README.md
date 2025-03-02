## Tic-Tac-Toe Reinforcement Learning Project

### Description
This project is an implementation of Reinforcement Learning (RL) applied to the game of Tic-Tac-Toe. Developed as part of my studies at NPUA, the goal is to train an RL agent that plays optimally against another RL agent or a human player.

### Key Components:
- **RL Agent**: Trains using Temporal-Difference learning with an ε-greedy strategy.
- **Human Player**: Provides the option for a human to compete with the RL agent.
- **Game Judge**: Organizes the gameplay between two agents (RL vs. RL or RL vs. Human).
- **State Management**: Handles board representation, state hashing, and game-ending checks.

### Workflow:
1. **Training**: Two RL agents train by playing against each other, tracking the win rates.
2. **Competition**: Trained agents compete to assess their effectiveness.
3. **Human Mode**: A human can challenge the trained RL agent for a game.

### Running the Project:
1. Clone or download the following files:
   - `state.py`
   - `player.py`
   - `judge.py`
   - `tic_tac_toe.py`
   
2. Run the main script:
   ```bash
   python tic_tac_toe.py
   ```

---

