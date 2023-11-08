# Hopper-Mujoco-
The task is to make a hopper, with 3 joints and 4 body parts, hop forward as fast as possible without falling on the floor. It has an 11-dimensional continuous state vector specifying position, derivatives of position, joint angles, etc., and a 3-dimensional continuous action vector that controls the actuators of the three joints.

This project is an implementation of a reinforcement learning agent using an actor-critic architecture for continuous
action spaces. The agent learns to interact with its environment, and the actor and critic networks are updated to
improve its policy and value function over time. The implementation is done using PyTorch, deep neural networks, soft target updates, and exploration strategies for training in a MuJoCo-based environment
