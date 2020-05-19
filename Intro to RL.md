# Types of algorithms

- Q-learning
- State-Action-Reward-State-Action (SARSA)
- Deep Q Network (DQN)
- Deep Deterministic Policy Gradent (DDPG)

## Intro

There are many types of algorithms for Reinforcement Learning (RL), but they all share the same core terms. Its important to understand that the agent cannot change data directly it can only observer data (immutable). The only thing the agent can do is perform actions and look at data.

![Annotation%202020-05-19%20091044.png](attachment:Annotation%202020-05-19%20091044.png)

- **agent** 
    - The entity that is running through the model/simulation.
    - A rat
- **action** 
    - The agent performs an action based on state and reward from previous actions. The agent's actions directly or indirectly affect the environment. Different algorithms choose actions differently.
    - The rat can move its head, arms, fingers, etc. Moving its body parts in a specific order may allow it to interact with world objects like picking up an object.
- **environment** 
    - The immutable unknown that may or may not be affected by various actions. 
    - The maze in which the rat operates. The rat does not control the room it is placed in.
- **reward** 
    - An immutable scalar value provided by the environment that helps the agent make decisions. 
    - After 3 actions, pulling a lever twice may result in cheese and ringing a bell may result in electrocution. What is the reward for pulling a lever, ringing bell, then pulling the lever again?
- **state**
    - Immutable, directly observable, environment data at a specific timeframe. 
    - The status of a door, light, fan, etc in the maze. The mouse can interpret this information to make future actions.



## Q-Learning


```python

```
