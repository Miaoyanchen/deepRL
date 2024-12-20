This project aims to provide a clear summary of deep reinforcement learning, which combines the principles of machine learning, reinforcement learning (RL), with deep learning techniques. This approach trains agents to make a sequence of optimal decisions over time. Deep reinforcement learning has been applied to a diverse range of fields, including robotics, video games, natural language processing, computer vision, education, transportation, finance, and healthcare. Our goal is to explain the core concepts and applications of deep reinforcement learning by reviewing the seminal paper published by Google DeepMin. This paper first introduced the concept of deep reinforcement learning, and our summary will break down its key materials for a comprehensive understanding. You can acess the project website using this link [here](https://miaoyanchen.github.io).

## Paper Overview

**Title:** "Human-level control through deep reinforcement learning"  
**Authors:** Volodymyr Mnih, Koray Kavukcuoglu, David Silver, et al.  
**Published:** 25 February 2015  
**Link:** [Nature Paper](https://www.nature.com/articles/nature14236)

## Preamble

In everyday activities such as conversation or driving, we continuously interact with and respond to our environment. This process—sensing changes and executing corresponding actions—forms the core of all learning and intelligence. This concept is foundational in reinforcement learning, where an agent learns to make decisions through a sequence of actions to achieve optimal results in a given environment. Reinforcement learning, a subfield of machine learning, focuses on training agents to perform complex tasks by making sequential decisions to maximize a notion of cumulative reward.

Deep reinforcement learning extends these concepts by integrating deep neural networks, allowing agents to handle real-world tasks with high-dimensional spaces. This README provides an introduction to the principles of deep reinforcement learning, particularly focusing on the deep Q-network (DQN) introduced by Mnih et al. in 2015, which combines Q-learning with deep neural networks to handle tasks like playing Atari 2600 games.

## Summary of Notations

| Variable   | Definition                                                              |
|------------|-------------------------------------------------------------------------|
| $s$        | state                                                                   |
| $a$        | action                                                                  |
| $t$        | discrete time step                                                      |
| $\pi$      | policy, decision rule                                                   |
| $s_t$      | state at time $t$                                                       |
| $a_t$      | action selected from a set of possible actions at time $t$              |
| $x_t$      | input to the emulator, typically a vector of pixel values               |
| $r_t$      | reward received at time $t$                                             |
| $\gamma$   | discount rate, typically set to 0.99                                    |
| $Q^*(s,a)$ | maximum expected return achievable by following the optimal policy $\pi$|
| $\theta$   | parameters of the deep neural network                                   |
| $R_t$      | cumulative reward at time $t$                                           |

## Reinforcement Learning Process

![Visualization of Reinforcement Learning](docs/diagram.png)

*Figure: Basic Structure of Reinforcement Learning*

Reinforcement learning allows agents (computers) to learn optimal behaviors through trial-and-error interactions within a structured environment. The agent observes the state of the environment, makes decisions (actions), receives rewards, and updates its policy based on the received rewards to maximize future rewards. This cycle continues until the agent achieves its goal, typically to maximize the cumulative reward.

For a detailed understanding and mathematical formulation of deep reinforcement learning, readers are encouraged to refer to our prject website and the full paper linked above.
