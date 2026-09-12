Cliff Walking — SARSA & Q-Learning

This repository contains Python implementations of two fundamental Model-Free Temporal-Difference (TD) control algorithms — SARSA and Q-Learning — demonstrated on Gymnasium’s CliffWalking-v1 grid-world environment.

The project explores the difference between on-policy and off-policy learning by training agents to navigate the cliff environment while maximizing their cumulative reward.

## 📸 Environment Preview
<img width="1156" height="480" alt="game" src="https://github.com/user-attachments/assets/44d95306-852a-4048-9a73-3556fbbbccc0" />




📌 Features

* On-Policy Control: sarsa.ipynb implements the SARSA algorithm.
* Off-Policy Control: Q_learning.ipynb implements the Q-Learning algorithm.
* Environment: Uses Gymnasium’s CliffWalking-v1 environment.
* Visualization: Includes real-time environment rendering using Pygame.
* Comparison: Allows the learning behavior of SARSA and Q-Learning to be observed and compared.

🛠️ Requirements & Setup

Make sure Python is installed, then install the required dependencies:

pip install gymnasium numpy pygame matplotlib

🚀 How to Run

Clone the repository:

git clone https://github.com/shreyarani01/cliff-walking-rl.git
cd cliff-walking-rl

Open either notebook in VS Code or Jupyter Notebook:

* sarsa.ipynb — SARSA implementation
* Q_learning.ipynb — Q-Learning implementation

Run the cells sequentially to train the agent and observe its learned path through the environment.

📚 Algorithms

SARSA

SARSA is an on-policy TD control algorithm that updates its Q-values using the action actually selected by the current policy.

Q-Learning

Q-Learning is an off-policy TD control algorithm that learns the optimal action values by considering the best possible next action.

The CliffWalking environment provides a simple way to visualize the behavioral differences between these two approaches.
