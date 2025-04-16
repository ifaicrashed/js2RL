# js-rl-gym

**js-rl-gym** is a Reinforcement Learning (RL) library written in JavaScript. This library provides a modular framework for creating and training RL agents in various environments. It supports both browser-based and Node.js usage.

## Project Structure

```plaintext
js-rl-gym/
│── index.html          # Browser Demo (Optional)
│── README.md           # Project Docs
│
├── js/                # All JavaScript Files
│   ├── environments/
│   │   ├── GridWorld.js    # Simple 2D Grid Environment
│   │   └── CartPole.js     # (Optional)
│   │
│   ├── agents/
│   │   └── DQN.js          # Deep Q-Learning Agent
│   │
│   └── core/
│       ├── Environment.js  # Base Environment Class
│       └── Agent.js        # Base Agent Class
│
└── examples/
    ├── train-gridworld.html  # Browser-Based Training Example
    └── train-cli.js          # Node.js CLI Training Example
