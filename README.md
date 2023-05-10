# Atari 2600 Game Solvers

This project focuses on using two Deep Reinforcement Learning algorithms to solve Atari 2600 games:
1. Double DQN with Prioritized Experience Replay (Proportional Prioritization).
2. Asynchronous Advantage Actor-Critic (A3C) algorithm.

## References
- The Double DQN with Prioritized Experience Replay (Proportional Prioritization) is based on the following research papers:
  - Mnih et al. [Human-level Control through Deep Reinforcement Learning](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf) [2015.02]
  - van Hasselt et al. [Deep Reinforcement Learning with Double Q-learning](https://arxiv.org/pdf/1509.06461.pdf) [2015.12]
  - Schaul et al. [Prioritized Experience Replay](https://arxiv.org/pdf/1511.05952.pdf) [2016.02]

- The A3C algorithm implementation is based on the following research papers:
  - Mnih et al. [Asynchronous Methods for Deep Reinforcement Learning](https://arxiv.org/pdf/1602.01783.pdf) [2016.06]
  - Babaeizadeh et al. [Reinforcement Learning through Asynchronous Advantage Actor-Critic on a GPU](https://arxiv.org/pdf/1611.06256.pdf) [2017.03]

## Environment
To run this project, you need the following environment:
- Python 2.7.x or 3.6.x
- NumPy 1.13.1
- TensorFlow 1.0.* or 1.1.* or 1.2.* or 1.3.*
- Keras 2.0.8
- SciPy 0.19.1 (For image pre-processing)
- H5py 2.7.1 (For saving or loading Keras models)
- Gym 0.9.3 (Provides Atari 2600 game environments)

These implementations utilize the power of Deep Reinforcement Learning to conquer Atari 2600 games using state-of-the-art algorithms.