# SDM366 Final Project

## Requirements Notes
- The second project original codes require mujoco >= 2.3.7 to run. However, if you use mujoco upper 3.0.0, it may need to edit line 593 of `mujoco_rendering.py`, changing `self.data.solver_iter` to `self.data.solver_niter`.
- The first project original codes require mujoco 3.1.3, if you are under this, you may need to edit the `xiaotian.xml` by adding `autolimits="true" `, and mujoco cannot be under 2.1.0.
- If encounter some errors about mujoco, try to uninstall the `mujoco-py`.

## Project 1: State Estimation for Robotic Manipulation with Vision

### ...

> Wait, for this part, you may encounter some problems about the pinocchio, and you can try to uninstall it, and change your channel to tuna, and install it again.

## Project 2: Reinforcement Learning for Inverted Pendulum with Vision

### Introduction

This project is to implement reinforcement learning for the inverted pendulum task with vision.

#### Single Inverted Pendulum

The file `project2_RL_train_pendulum_edit` is created by gym official pendulum model and visualized by mujoco. 
The visualization and training process are in the same file. 
It is a simple model to stabilize a single inverted pendulum.

And the file `project2_RL_train_pendulum_edit_v2` is a better model to stabilize a single inverted pendulum. 
Both of them have attempted to use various models and hyperparameters to train the model. 
And for the next task, the version 2 model can stabilize the pendulum with higher initial velocity.

For the swing-up task, the file `project2_RL_train_swing_pendulum` uses a method call `throw and catch` to swing up the pendulum.
There are two different agents to work cooperatively to swing up the pendulum. 
The thrower swings up the pendulum and the catcher stabilizes it.

#### Double Inverted Pendulum

The file `project2_RL_train_double_pendulum` is created by gym official double pendulum model and visualized by mujoco.
It can stabilize the double inverted pendulum for a long time.

For advanced tasks, swing-up at any phase and stabilize the pendulum, the file `project2_RL_train_swing_d_p_catch` and `project2_RL_train_swing_d_p_throw` are created.

## About the project
This is the final project of SDM366, and it is a group project.
So, the complete project is in another repository, and the link is [Oops, it is still hidden!]().