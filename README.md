# Deep Reinforcement Learning Trading Bot

This repository contains the code for a Deep Reinforcement Learning (DRL) trading bot developed using Python. The bot is trained and tested on the S&P 500 index and selected tickers, utilizing the Proximal Policy Optimization (PPO) and Advantage Actor-Critic (A2C) algorithms.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to develop and compare the performance of two DRL algorithms (PPO and A2C) for trading the S&P 500 index. The bot uses custom indicators such as Simple Moving Average (SMA), Relative Strength Index (RSI), and On-Balance Volume (OBV) for decision making.

## Features

- **Custom Environment**: The environment is tailored for trading with the S&P 500 index and selected tickers.
- **Custom Indicators**: SMA, RSI, and OBV are used as input features.
- **DRL Algorithms**: PPO and A2C algorithms are implemented and compared.
- **Visualization**: Performance comparison of PPO and A2C algorithms.

##Results
PPO RESULTS
![download](https://github.com/AdamHassouni/DRL_Trading_Bot/assets/122727246/3afe5508-6181-425d-b997-0dc6402d0bc7)
A2C RESULTS
![download](https://github.com/AdamHassouni/DRL_Trading_Bot/assets/122727246/8c1ccaa2-9ad0-49bb-b29b-b5e9d16079d5)
PPO vs A2C
![download](https://github.com/AdamHassouni/DRL_Trading_Bot/assets/122727246/910da940-6162-48c4-80bd-d7f23bf75cc0)


## Installation

To set up the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/AdamHassouni/DRL_Trading_Bot.git
cd DRL_Trading_Bot
pip install -r requirements.txt


