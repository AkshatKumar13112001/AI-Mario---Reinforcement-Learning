# Super Mario Bros Reinforcement Learning

We create an AI that's able to play Super Mario Bros be using Double Deep Q Network Reinforcement Learning algorithm to do this.


## Features

**DDQN with CNN**

The project implements Double Deep Q Learning using Convolutional Neural Networks to facilitate efficient learning and decision-making.

**Epsilon-Greedy Approach**

To address the Explore-Exploit dilemma, the agent employs an Epsilon-Greedy Approach, balancing between exploiting known strategies and exploring new ones.

Make sure you activate the environment.

```bash
conda activate smbrl
```

**NES Emulation**

The game environment is emulated using an API based on OpenAI’s Gym reinforcement learning library, providing a realistic environment for the agent to learn and play in.

**Training**

The model is trained through 50,000 iterations, during which the AI learns and improves its gameplay strategies until it successfully completes the level.


