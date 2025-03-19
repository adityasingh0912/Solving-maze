# Solving-maze
## Q-Learning Maze Solver

This project implements a Q-learning agent to navigate a maze using reinforcement learning. The agent learns an optimal policy through interaction with the environment, using a reward-based system.

## 🚀 Features
- **Q-learning Algorithm**: Implements tabular Q-learning with an epsilon-greedy exploration strategy.
- **Maze Representation**: Uses a 2D NumPy array for the environment.
- **Visualization**: Renders the maze and the learned path.
- **Hyperparameter Tuning**: Adjustable parameters for learning rate, discount factor, and exploration decay.

## 📌 Requirements
Ensure you have the following dependencies installed:
```bash
pip install numpy matplotlib
```

## 🏗️ Installation
Clone the repository and navigate to the project folder:
```bash
git clone https://github.com/your-repo/q-learning-maze.git
cd q-learning-maze
```

## 🏃‍♂️ Usage
Run the Python script to train the Q-learning agent and visualize the learned path:
```bash
python q_learning_maze.py
```

## 🎯 How It Works
1. The agent starts at the predefined start position.
2. It chooses actions based on the Q-table and exploration strategy.
3. Rewards are assigned based on movement, goal reaching, or hitting obstacles.
4. The Q-table is updated using the Bellman equation.
5. After training, the agent follows the optimal path to reach the goal.

## 🔧 Hyperparameters
You can tweak the following parameters in `q_learning_maze.py`:
```python
alpha = 0.1       # Learning rate
gamma = 0.9       # Discount factor
epsilon = 1.0     # Exploration probability
epsilon_decay = 0.995
```

## 📊 Results
The trained agent successfully finds the shortest path to the goal in a given maze. Use `visualize_path()` to see the learned policy.

## 🏆 Future Improvements
- Implement **dynamic learning rate adjustment**
- Introduce **obstacle penalties** to encourage efficient navigation
- Extend to **larger mazes** and **3D environments**

## 🤝 Contributing
Feel free to fork the repository, submit issues, and create pull requests!

## 📜 License
This project is open-source and licensed under the MIT License.

---
🚀 Happy Coding!

