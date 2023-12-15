# Physarum-Polycephalum-Network-Simulation
Physarum Polycephalum is a unicellular organism that exhibits swarm like intelligence in it's ability to form efficient food networks. The goal of this project is to demonstrate how interactions at a micro level lead to the emergence of complex emergent behaviours observed in real slime molds.

The core functionality of the simulation is mimicking the protoplasmic trails of Physarum Polycephalum. Agents within the simulation represent parts of the slime mold moving and interacting to form networks. The behaviour of these agents is regulated by three key parameters:

- Sensory Angle: Determines the breadth of each agent's sensory perception, influencing its ability to detect environmental stimuli and trail pheromones.

- Sensory Offset: Defines the distance ahead of each agent where it senses its environment. This parameter plays a crucial role in the direction and movement of the agent.

- Turn Angle: Influences the agent's ability to turn and change direction in response to the detected stimuli, allowing for dynamic navigation and network formation.

In addition to agent parameters the simulation environment is controlled by two main factors:

- Diffusion Rate: Affects the spread of pheromone trails left by agents. Higher diffusion rates lead to wider and more dispersed trails, influencing the likelihood of other agents encountering and following these trails.

- Evaporation Rate: Determines the longevity of the pheromone trails. Faster evaporation rates result in shorter-lived trails, requiring agents to constantly explore and adapt to new paths, avoiding reliance on outdated information.

https://samjsnn.github.io/Physarum-Transport-Network/
