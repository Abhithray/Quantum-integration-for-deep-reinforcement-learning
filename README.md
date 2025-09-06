# Quantum Integration for Deep Reinforcement Learning

This repository provides a **hybrid Deep Reinforcement Learning (DRL) + Quantum approach** using **Qiskit** and **Stable-Baselines3**. The project integrates the **Quantum Approximate Optimization Algorithm (QAOA)** with RL agents to improve anomaly detection and optimization performance.

---

## ✨ Key Features
- 🧠 Hybrid quantum-classical reinforcement learning  
- 📊 Benchmark with **UNSW-NB15 dataset**  
- ⚡ Compare classical DRL vs quantum-integrated DRL  
- 🔍 Metrics: Accuracy, Precision, Recall, F1-score  
- 📈 Resource profiling with `memory-profiler` and `psutil`  

---

## 🛠️ Tech Stack
- **Python 3.9+**
- [Qiskit](https://qiskit.org/) – Quantum circuits & QAOA
- [Stable-Baselines3](https://stable-baselines3.readthedocs.io/) – RL algorithms
- [Gym](https://gym.openai.com/) – Environments
- **Pandas, NumPy, Scikit-learn** – Preprocessing & analysis

---

## 📂 Project Structure
├── DRL_source.ipynb # Main notebook with quantum + DRL experiments
├── requirements.txt # Dependencies
└── README.md # Documentation

--

## ⚙️ Installation
Clone the repo and install dependencies:
```bash
git clone https://github.com/Abhithray/Quantum-integration-for-deep-reinforcement-learning.git
cd Quantum-integration-for-deep-reinforcement-learning
pip install -r requirements.txt
