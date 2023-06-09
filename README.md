# Car RL Agent in 2D Environment with Evolutionary ANN
This is a Unity project that implements an RL (Reinforcement Learning) agent to control a car in a 2D environment. The RL agent is based on an Evolutionary Artificial Neural Network (EANN) that learns to drive the car by maximizing a reward function. The goal is to achieve the maximum distance possible without crashing the car.

![Demo](https://user-images.githubusercontent.com/66371106/233305659-6a6f9b70-a4e1-4a58-a005-fc95ff6ead96.gif)

# Installation
-Clone or download the project from the GitHub repository

-Open the project in Unity

-Go to the "Scenes" folder and open the "Main" scene

-Press the play button to start the simulation

# Usage
The RL agent will start learning to drive the car from scratch. You can observe its behavior in the Unity editor's Game window. The agent uses the EANN to decide the car's actions, such as accelerating, braking, or turning left/right.

You can change the simulation's parameters in the "SimulationManager" game object in the Unity editor's Hierarchy window. For instance, you can adjust the number of cars, the duration of each simulation, and the number of generations.

# Results
The RL agent will improve its performance over time as it learns from its mistakes. You can visualize the agent's learning progress by checking the graphs in the "Charts" tab of the "SimulationManager" game object.

# Courses
![Courses](https://user-images.githubusercontent.com/66371106/233305832-7a60743d-0636-48c2-8f87-c30b80957ac1.png)


# Credits
This project was inspired by the work of OpenAI and their reinforcement learning algorithms. The EANN implementation is based on the NEAT (NeuroEvolution of Augmenting Topologies) algorithm by Stanley and Miikkulainen (2002). The Unity environment was created using assets from the Unity Asset Store.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.
