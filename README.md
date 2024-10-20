# Multi-Agent Reinforcement Learning in a Custom Environment

This repository contains an implementation of Multi-Agent Reinforcement Learning (MARL) in a custom-built environment. The environment is designed from scratch using only numpy, ensuring efficiency and flexibility for various MARL experiments. Additionally, the project features a custom visualization tool created with shapely and "matplotlib" to effectively illustrate the agents' interactions and environment dynamics.

## Features:

- **Custom Environment**: Built entirely using **numpy**, providing a lightweight and easily modifiable environment.
- **Multi-Agent Support**: Capable of handling multiple agents with complex interactions.
- **Custom Visualization**: Visualize the environment and agent behaviors using **shapely** and **matplotlib[scatter plot]** for clear and insightful representations.
## Agent:
### Team:
- 'L' : Team Left; Index: '0'
- 'R' : Team Right; Index: '1'
### Players:
- 'pg' : Point Guard
- 'sg' : Shooting Guard
- 'sf' : Small Forward
- 'pf' : Power Forward
- 'c'  : Center
### Movement:
- right = 0
- forward - right = 1
- forward = 2
- forward -left = 3
- left = 4
- left - backward = 5
- backward = 6
- right - backward = 7
- does nothing = 8
## Visualization

The environment visualization will be rendered automatically, showing real-time interactions between the agents. Option to visualize the interaction in 3 different mode:

1. Random
2. Model
3. Log

![alt text](https://github.com/Vincent9339/marl-basketball/blob/master/img/image-20240817104031010.png?raw=true)



## License

Feel free to use, modify, and distribute this work.

