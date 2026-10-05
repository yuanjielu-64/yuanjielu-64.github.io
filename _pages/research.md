---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## 🌟 What I Do

I aim to build **intelligent navigation systems** that enable robots to operate autonomously in complex, unstructured environments.

---

## 🔬 Research Themes

* ***Foundation Models for Embodied AI***  
Developing LLM/VLM-based systems that connect perception, reasoning, and action, enabling robots to interpret complex environments and adapt their decisions to changing conditions.

* ***World Models for Embodied Intelligence***  
Learning action-conditioned models of physical environments and robot behavior to predict future states, anticipate interaction outcomes, and support decision-making under uncertainty.

* ***Deep Reinforcement Learning for Robot Control***  
Developing adaptive control policies for mobile and legged robots, with a focus on sample-efficient learning, hierarchical control, and transfer from simulation to the real world.

* ***Machine Learning-Augmented Motion Planning***  
Combining learned representations, prior experience, and classical planning to generate efficient, dynamically feasible motions in cluttered and challenging environments.

---

## 🚀 Future Directions

My future research will connect foundation models, predictive world models, and reinforcement learning to enable robots to adapt to unfamiliar environments, reason about the consequences of their actions, and operate reliably under physical constraints.

---

## 🤖 Hardware Platforms

I work with diverse robot platforms to validate algorithms in both simulation and real-world environments.

| Robot | Image | Type | Use Case |
|:------|:------:|:------|:----------|
| **Unitree Go1** | <img src="/images/go1.png" width="180"/> | Quadruped | Visual–LiDAR fusion, RL locomotion |
| **Unitree Go2** | <img src="/images/go2.png" width="180"/> | Quadruped | VLM navigation, cross-modal perception |
| **Unitree G1** | <img src="/images/G1.png" width="180"/> | Humanoid | LLM-guided policy learning |
| **Clearpath Jackal** | <img src="/images/jackal1.png" width="180"/> | Wheeled UGV | Real-world navigation testing |
| **Clearpath Husky** | <img src="/images/husky.png" width="180"/> | Wheeled UGV | Outdoor mapping, multi-sensor fusion |


---

## 🛠️ Simulation Environments

I design and use multiple simulation platforms for both classical planning and learning-based navigation.

| Environment | Image | Description |
|:-------------|:------:|:------------|
| **Gazebo** | <img src="/images/gazebo.png" width="300"/> | Classic ROS-based simulator for wheeled robots, supporting costmaps, sensor fusion, and realistic physics. |
| **Isaac Gym** | <img src="/images/isaacgym.png" width="300" style="max-width:100%;height:auto;aspect-ratio:16 / 9;object-fit:cover;object-position:center bottom;"/> | GPU-accelerated simulation for large-scale reinforcement learning and policy optimization. |
| **Isaac Sim** | <img src="/images/isaacsim.png" width="300"/> | High-fidelity NVIDIA Omniverse simulator for perception, dynamics, and multi-robot coordination. |
| **Newton** | <video width="300" style="max-width:100%;height:auto;" autoplay muted loop playsinline preload="metadata" poster="/images/newton_navigation_cover.png" aria-label="Quadruped navigation in Newton simulation"><source src="/images/newton_navigation_loop.mp4" type="video/mp4"><img src="/images/newton_navigation_cover.png" width="300" alt="Quadruped navigation in Newton simulation"></video> | Legged locomotion simulation and policy evaluation across diverse terrains. |
| **MuJoCo** | <video width="300" style="max-width:100%;height:auto;" autoplay muted loop playsinline preload="metadata" poster="/images/mujoco_navigation_cover.png" aria-label="Quadruped navigation in MuJoCo simulation"><source src="/images/mujoco_navigation_loop.mp4" type="video/mp4"><img src="/images/mujoco_navigation_cover.png" width="300" alt="Quadruped navigation in MuJoCo simulation"></video> | Closed-loop simulation of robot dynamics, locomotion control, and autonomous navigation. |
| **mjlab** | <video width="300" style="max-width:100%;height:auto;" autoplay muted loop playsinline preload="metadata" poster="/images/mjlab_go2_simulation_cover.png" aria-label="Unitree Go2 locomotion in mjlab simulation"><source src="/images/mjlab_go2_simulation.mp4" type="video/mp4"><img src="/images/mjlab_go2_simulation_cover.png" width="300" alt="Unitree Go2 in mjlab simulation"></video> | Unitree Go2 locomotion simulation using mjlab and MuJoCo Warp. |
| **Custom Terrains** | <img src="/images/terrian.png" width="300"/> | Procedurally generated terrains for testing locomotion, stability, and adaptive control. |
| **Self-design Simulation** | <video width="300" style="max-width:100%;height:auto;" autoplay muted loop playsinline preload="metadata" poster="/images/dromos_simulation_cover.png" aria-label="Multi-goal motion planning simulation"><source src="/images/dromos_simulation_loop.mp4" type="video/mp4"><img src="/images/dromos_simulation_cover.png" width="300" alt="Multi-goal motion planning simulation"></video> | self-design simulation using C++ for motion planning or multi-goal motion planning. |

