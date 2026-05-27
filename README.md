# RL Theory Notes

This repository collects my notes, diagrams, and small implementations from my public learning series on Reinforcement Learning, RL theory, Linear MDPs, LSVI-UCB, and RLHF.

The goal is to build a structured roadmap for learning RL from fundamentals to modern theory.

## Roadmap

### 1. RL Fundamentals
- What makes RL different from normal machine learning?
- States, actions, policies, models, rewards
- Model-based vs model-free RL
- Multi-armed bandits
- Markov Decision Processes

### 2. Bellman Equations and Planning
- Value functions
- Policy evaluation
- Bellman equations
- Bellman optimality equation
- Value iteration
- Infinite-horizon discounted MDPs

### 3. Concentration Inequalities
- Hoeffding's inequality
- Bernstein's inequality
- Martingales
- Azuma-Hoeffding inequality
- Azuma-Bernstein inequality

### 4. Bandits and Exploration
- Exploration vs exploitation
- Epsilon-greedy
- Optimism in the face of uncertainty
- UCB algorithm
- Bandits vs RL exploration

### 5. UCBVI and Regret
- UCBVI
- Optimistic Bellman backups
- Bonus design
- Regret as a sum of bonuses
- Near-optimal guarantees

### 6. Function Approximation
- Why tabular RL breaks
- Features φ(s,a)
- Linear function approximation
- Misspecification
- Generalization in large state spaces

### 7. Linear MDPs and LSVI
- Linear MDP assumptions
- Why Q-functions become linear
- Transition linearity
- Least-Squares Value Iteration
- LSVI-UCB

### 8. RLHF
- Why RLHF exists
- Preference-based MDPs
- Reward modeling
- RLHF loop
- Active learning in RLHF
- Feedback types

## LinkedIn Series

I am also publishing this material as a LinkedIn learning series.

- [RL Fundamentals Series](https://www.linkedin.com/posts/r-r-pandey_links-to-rl-fundamental-series-share-7430168702962024448-4CCX/?utm_source=share&utm_medium=member_desktop&rcm=ACoAADxS0aABzU_C33hh8Cyp-QM6yl2M_xwYyHc)
- [RLHF Series](https://www.linkedin.com/posts/r-r-pandey_links-to-rlhf-series-share-7446404311468744704-JkqM/?utm_source=share&utm_medium=member_desktop&rcm=ACoAADxS0aABzU_C33hh8Cyp-QM6yl2M_xwYyHc)

## Notebooks

Planned implementations:

- Multi-armed bandit with UCB
- Value iteration in gridworld
- Q-learning demo
- Simple reward-modeling example for RLHF

## Author

Rajeev Ranjan Pandey
