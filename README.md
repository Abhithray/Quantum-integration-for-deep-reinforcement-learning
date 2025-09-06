# Quantum-integration-for-deep-reinforcement-learning

This project explores the integration of Quantum Approximate Optimization Algorithm (QAOA) with Deep Reinforcement Learning (DRL) to enhance anomaly detection in network traffic datasets. By leveraging quantum circuits alongside classical RL agents, the framework aims to improve accuracy, efficiency, and generalization in cybersecurity use cases.

🚀 Features

Hybrid DRL-Quantum approach using Qiskit’s QAOA and Stable Baselines3 RL agents

Benchmark datasets: UNSW-NB15 training & testing sets

Classical + Quantum comparison for anomaly detection tasks

Performance metrics: Accuracy, precision, recall, F1-score

Resource monitoring with memory-profiler and psutil

🛠️ Tech Stack

Python 3.x

Qiskit (Quantum Circuits, QAOA)

Stable-Baselines3 (DRL algorithms like PPO, DQN)

Pandas, NumPy, Scikit-learn (data preprocessing, feature selection)

Gym (simulation environments)

📂 Project Structure
Quantum-integration-for-deep-reinforcement-learning/
│── DRL_source.ipynb        # Main notebook with experiments
│── requirements.txt        # Dependencies
│── README.md               # Project documentation

Clone the repository and install dependencies:
git clone https://github.com/Abhithray/Quantum-integration-for-deep-reinforcement-learning.git
cd Quantum-integration-for-deep-reinforcement-learning
pip install -r requirements.txt

▶️ Usage

Open DRL_source.ipynb in Jupyter or Google Colab.

Load the UNSW-NB15 dataset.

Train classical DRL agents (e.g., PPO, DQN).

Train hybrid DRL + QAOA agents.

Compare results across methods.

📊 Results

Hybrid quantum-classical models achieved improved anomaly detection performance on benchmark datasets.

Quantum-enhanced optimization demonstrated better convergence in certain environments compared to purely classical RL.

(Detailed plots and evaluation metrics can be found inside the notebook.)

🔮 Future Work

Extend to more complex environments (e.g., CICIDS 2017 dataset).

Explore real quantum hardware execution beyond simulation.

Investigate scalability and noise resilience of hybrid DRL models.
