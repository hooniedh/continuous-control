# continuous control
This is my solution to Udacity reinforcement learning nanodegree **continuous control** project. Deep Q networks are used.
### environment
The environment is provided by Udacity and it is made from the Unity ML agent (https://github.com/Unity-Technologies/ml-agents).
There are 20 agents in this environment. Each agent is a double jointed arm that can move to target locations. 
- The environment returns 37 floats as the states in each step.
- There are four actions available to an agent and the actions are continuous between -1 and 1.
- A reward of +0.1 is provided for each step that the agent's hand is in the goal location
   
The environment is considered as solved if the average reward over all the agents over 100 consecutive episodes is greater or equal to +30.
  
### getting started
This project depends on Pytorch and Unity ML agents.
- Pytorch: https://pytorch.org/
- Unity ML agents: https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md
- Udacity navigation environment: https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation

**It is important to note that the agent provided by Udacity is only compatible with Unity ML agent version 0.4.0. It can be downloaded from https://github.com/Unity-Technologies/ml-agents/releases.**

### instructions
A train can be started by running training.py. The path and the executable of the environment should be passed in as the first argument. For example if the environment is Reacher.exe (Windows executable) in the Reacher_Windows_x86_64 directory, you can run the script like this

```
python training.py Reacher_Windows_x86_64/Reacher.exe
```
