# PPO Trading Agent on Apple Stock Data

This project implements a basic reinforcement learning trading agent using the PPO algorithm from `stable-baselines3`. The environment is based on `gym-anytrading` using historical Apple (AAPL) stock data.

## Features

- Trains a PPO agent to buy/sell/hold based on price movements
- Simulates trades with 10% of available balance
- Visualizes trading actions and balance over time

## Getting Started

### Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
