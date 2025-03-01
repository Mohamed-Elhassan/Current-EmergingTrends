# Current-EmergingTrends

### Project Overview
This project implements a reinforcement learning agent that navigates a maze environment using deep Q-learning. The goal is for the agent (represented as a pirate) to find the treasure by exploring the maze, receiving rewards or penalties based on its actions. The agent learns by interacting with the environment and adjusting its behavior over time using the Q-learning algorithm.

### Briefly explain the work that you did on this project:
For this project, I was provided with the following code files:

* TreasureMaze.py: This class defines the maze environment, including the initial maze layout, agent movement, reward system, and methods for resetting the game and visualizing the environment.
* GameExperience.py: This class stores episodes of the agent’s experience, which is used for learning by experience (exploration). It includes methods for predicting the agent’s next action and storing the results of each action to update the Q-values.
* Elhassan_Mohamed_ProjectTwo.ipynb: The Jupyter notebook provided a basic framework for running the deep Q-learning agent, with sections that were intended to set up the agent, initialize the environment, and run training episodes. However, I had to make changes to the notebook to integrate the TreasureMaze.py and GameExperience.py classes, implement the Q-learning training loop, and adjust the reward structure to make the project functional.

### Changes I made to the notebook include:

Connecting the reinforcement learning agent to the environment.
Implementing the deep Q-learning algorithm to train the agent over multiple episodes.
Visualizing the agent’s progress and tracking its performance.
Adjusting the reward structure based on agent actions and learning dynamics.

### What do computer scientists do and why does it matter?

Computer scientists solve problems by designing algorithms and systems that process data efficiently. In this project, I applied algorithms to train an agent to solve a specific problem—navigating a maze. This kind of work is critical in areas such as artificial intelligence, machine learning, and robotics, where systems need to make autonomous decisions based on data and past experiences. The ability to create intelligent agents that can adapt to their environments is a key aspect of modern computing.

### How do I approach a problem as a computer scientist?

As a computer scientist, I approach problems by breaking them down into smaller components. I start by analyzing the environment, defining the system’s constraints, and selecting appropriate algorithms to solve the problem. In this case, I used reinforcement learning because it’s well-suited for problems where an agent learns from interacting with an environment. I also worked on adjusting the reward structure and handling edge cases like invalid actions or revisiting cells, which are essential for ensuring the agent learns correctly.

### What are my ethical responsibilities to the end user and the organization?

As a computer scientist, my ethical responsibilities include ensuring the systems I build are secure, fair, and transparent. For the end user, this means providing predictable, safe, and responsible AI behavior. In this project, the agent’s behavior is controlled through rewards and penalties to prevent it from exploiting loopholes. For the organization, I need to ensure that the solution is scalable, efficient, and reliable, making sure it can be used in real-world applications and integrated with other systems. Additionally, I should respect user privacy and ensure that the data used for training the agent is handled ethically.
