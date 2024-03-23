# Reinforcement Ball Balancing Slab

<p align="center">
  <img src="data/0.png" alt="Project Logo Cover" width="1500"/>
</p>


---------------------------------------------


## About this Project:
The project depicted in the image involves the development of a ball balancing slab system utilizing a reinforcement learning agent. It's an artificial intelligence application programmed in C# and implemented with the Unity game engine.

<p align="center">
  <img src="data/Thumbnail.png" alt="Project Title" width="1500"/>
</p>


---------------------------------------------


## Game Rules:
The project is designed to demonstrate a reinforcement learning (RL) scenario where an AI agent is tasked with balancing a ball on a slab. The agent receives a small positive reward incrementally for each time step that the ball stays on the slab, encouraging the agent to learn strategies for maintaining balance. Conversely, a negative reward is given when the ball falls off, which helps the agent to learn from its mistakes and avoid actions leading to such an outcome. The control mechanism allows the slab to be rotated along two axes, which adds complexity to the task and requires the agent to develop a nuanced understanding of the physics involved.

<p align="center">
  <img src="data/2.png" alt="2" width="1500"/>
</p>


---------------------------------------------


## What is Proximal Policy Optimization (PPO):
Proximal Policy Optimization (PPO) is a policy gradient method for reinforcement learning which alternates between sampling data through interaction with the environment and optimizing a "surrogate" objective function using stochastic gradient ascent. Developed by OpenAI, PPO aims to improve upon the stability and sample efficiency of previous methods like Trust Region Policy Optimization (TRPO) but with simpler implementation and better general performance.


---------------------------------------------


## Key aspects of  include:

    • Clipped Objective: Limits policy updates to prevent excessive changes.
    • Multiple Updates: Allows several mini-batch updates per data sample for better efficiency.
    • KL Penalty/Clipping: Ensures policy updates stay within a "safe" range to maintain training stability.
    • Advantage: PPO is favored for its simplicity, efficiency, and consistent performance across various RL tasks.

<p align="center">
  <img src="data/3.png" alt="3" width="1500"/>
</p>


---------------------------------------------


## Results:

<p align="center">
  <img src="data/4.png" alt="4" width="1500"/>
</p>


---------------------------------------------


## My Project Video Demonstration:

<p align="center">
  <a href="https://www.linkedin.com/posts/tvharikrishna_reinforcementlearning-machinelearning-neuralnetwork-activity-7118597093476196352-Q_cM?utm_source=share&utm_medium=member_desktop">
    <img src="https://img.shields.io/badge/Video-Watch How AI Slab is Balancing-blue" alt="Video"/>
  </a>
</p>

---------------------------------------------
