# Autonomous Car Simulation (TensorFlow)

A virtual traffic environment for training autonomous cars using reinforcement learning.The agent learns to navigate dynamic environments with moving obstacles, achieving successful obstacle avoidance.

### Demo:

#### with static obstacles:

![Static Obstacles Demo](./resources/static_demo.gif)

#### with dynamic (moving) obstacles:

![Static Obstacles Demo](./resources/dynamic_demo.gif)

### Features:

- Designed with TensorFlow for efficient training.
- Utilizes reinforcement learning algorithms (e.g., Q-Learning) for autonomous car behavior optimization.
- Simulates dynamic traffic environments with customizable numbers of moving obstacles for obstacle avoidance training.


### Dependencies:

| Library |	Description |
|--|--|
| P5.js |	A JavaScript library for creative coding. Used in this project for easy visualization of the virtual traffic environment. |
| TensorFlow.js |	A JavaScript library enabling machine learning on the web browser. Used for implementing reinforcement learning algorithms for the autonomous car agent. |
| Collide2d.js |	A library for efficient collision detection between objects in 2D space. Useful for accurately simulating collisions between the car and obstacles. |
