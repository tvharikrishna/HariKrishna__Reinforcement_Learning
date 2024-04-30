<p align="right">© Documentation by tvharikrishna</p>
<p align="right">1 minute read 📚</p>

<h1 align="left">🔻 Repository Details</h1>
<p align='justify'>This repository contains various simulations on agents that currently don't think but, using state-of-the-art simulators like Nvidia Isaac Gym, PyBullet, MuJoCo, and Unity. I will train different sets of Reinforcement Learning algorithms on these agents across all these simulators and test all algorithms.</p>

<h2 align="center">🔻 Simulation Naming Convention</h2>
<table align="center">
<thead>
<tr>
<th align="center">Naming Prefix</th>
<th align="center">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><strong>HKIsaac__</strong></td>
<td align="right">Simulations in Isaac Gym</td>
</tr>
<tr>
<td align="left"><strong>HKPyBullet__</strong></td>
<td align="right">Simulations in PyBullet</td>
</tr>
<tr>
<td align="left"><strong>HKMuJuCo__</strong></td>
<td align="right">Simulations in MuJoCo</td>
</tr>
</tbody>
</table>

<h2 align="left">🔻 Frameworks & Agents</h2>
<ul>
<li><a href="https://www.nvidia.com/en-us/industries/robotics/">Nvidia AI for Robotics</a></li>
<li><a href="https://github.com/NVIDIA-Omniverse/OmniIsaacGymEnvs">OmniIsaacGymEnvs Github</a></li>
<li><a href="https://developer.nvidia.com/nvidia-omniverse">Nvidia Omniverse</a></li>
<li><a href="https://developer.nvidia.com/isaac-sdk">Nvidia Isaac</a></li>
<li><a href="https://docs.omniverse.nvidia.com/isaacsim/latest/isaac_gym_tutorials/index.html">Nvidia Isaac Gym Documentation</a></li>
<li><a href="https://github.com/google-deepmind/dm_control">Google Deep Mind Control Suite</a></li>
<li><a href="https://mujoco.org/">MuJoCo</a></li>
<li><a href="https://pybullet.org/wordpress/">PyBullet</a></li>
</ul> <br>

<h2 align="left">🔻 What is Reinforcement Learning?</h2>
<p align='justify'>Reinforcement Learning (RL) is a type of machine learning where agents learn to make decisions by interacting with an environment to maximize some notion of cumulative reward. It's characterized by trial-and-error, feedback, and the balance between exploration of uncharted territory and exploitation of current knowledge.</p>
<p align="center">
    <img src="readme_data/RL_1.png" alt="Overview of Reinforcement Learning" width="800"/>
</p> <br>

<h2 align="left">🔻 What are Agents?</h2>
<p align='justify'>An Agent is an entity capable of perceiving its environment, making decisions on what actions to take, and learning from the outcomes of these actions. The agent's goal is to find the best strategy, or policy, that will maximize the cumulative rewards over time. This process involves observing the environment, executing actions, receiving rewards, and updating the policy based on the learned experiences.</p>
<p align="center">
    <img src="readme_data/RL_2.png" alt="Diagram explaining agent interactions" width="800"/>
</p> <br>

<h2 align="left">🔻 RL Pipeline</h2>
<p align="center">
    <img src="readme_data/RL_3.png" alt="Reinforcement Learning Pipeline" width="800"/>
</p>

<p align="center">Explanation of the Reinforcement Learning Pipeline:</p>

- **Environment:** Illustrated by a globe, it represents the world or context in which the RL agent operates. In RL, the environment is where the agent performs actions and receives feedback in the form of states and rewards.

- **Reward:** Shown as a bag of money with a dollar sign, this symbolizes the reward function. In RL, rewards are given to the agent for performing certain actions, which guide the agent to learn the optimal policy. The reward is the feedback signal used to quantify the success of an action taken in a given state.

- **Agent:** Depicted as a neural network, this is the learner or decision-maker. The agent decides what actions to take to achieve its goal, based on the policy it learns from interacting with the environment.

- **Training:** Illustrated with a barbell being lifted by the word "agent", this represents the process of learning. The agent is metaphorically "exercising" through training to improve its policy. The action of training involves the agent interacting with the environment, receiving rewards, and adjusting its policy accordingly.

- **Deployment:** The final icon is a robot, representing the deployment phase where the trained agent is put into action in the real world or a production environment. The robot implies that the agent is now capable of performing tasks autonomously.

<hr> <br> <br>

<p align="center">
    <img src="readme_data/hk_quote.png" alt="Inspiring quote related to computer vision and robotics" width="1500"/>
</p>
