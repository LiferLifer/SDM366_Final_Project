# SDM366 Final Project

## Requirements Notes
- The second project original codes require mujoco >= 2.3.7 to run. However, if you use mujoco upper 3.0.0, it may need to edit line 593 of `mujoco_rendering.py`, changing `self.data.solver_iter` to `self.data.solver_niter`.
- The first project original codes require mujoco 3.1.3, if you are under this, you may need to edit the `xiaotian.xml` by adding `autolimits="true" `, and mujoco cannot be under 2.1.0.
- If encounter some errors about mujoco, try to uninstall the `mujoco-py`.

## Project 1: State Estimation for Robotic Manipulation with Vision

### ...

## Project 2: Reinforcement Learning for Inverted Pendulum with Vision

### Introduction

This project is to implement reinforcement learning for the inverted pendulum task with vision.

The file `project2_RL_train_pendulum_edit` is created by gym official pendulum model and visualized by mujoco. The visualization and training process are in the same file.

### Models

Up to now, the model with the best performance is `lifer_official_model0.pth`, just try it :)