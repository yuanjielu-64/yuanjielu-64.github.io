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

* ***Foundation Models for Intelligent Decision-Making***  
Developing LLM and VLM-based systems for adaptive reasoning and planning. Focusing on prompt engineering, fine-tuning with domain-specific data, and real-time inference optimization for sequential decision-making tasks.

* ***Deep Reinforcement Learning for Adaptive Control***  
Designing model-free and hierarchical RL algorithms for continuous control problems. Investigating policy learning, reward shaping, and sim-to-real transfer methods for deployment in complex, dynamic environments.

* ***Learning-based Motion Planning***  
Creating neural planning methods that leverage learned representations for efficient path generation. Developing learned heuristics, memory-augmented frameworks, and hybrid approaches combining classical and learning-based techniques.

---

## 🚀 Future Directions

My future research aims to advance **foundation models and reinforcement learning** for more complex decision-making scenarios.

**Key directions:**
- Scaling LLM/VLM reasoning to longer horizons and multi-agent systems
- Sample-efficient RL for high-dimensional continuous control tasks
- Bridging the gap between learned policies and real-world deployment

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
| **Isaac Gym** | <img src="/images/isaacgym.png" width="300"/> | GPU-accelerated simulation for large-scale reinforcement learning and policy optimization. |
| **Isaac Sim** | <img src="/images/isaacsim.png" width="300"/> | High-fidelity NVIDIA Omniverse simulator for perception, dynamics, and multi-robot coordination. |
| **Newton** | <video width="300" style="max-width:100%;height:auto;" autoplay muted loop playsinline preload="metadata" poster="/images/newton_navigation_cover.png" aria-label="Quadruped navigation in Newton simulation"><source src="/images/newton_navigation_loop.mp4" type="video/mp4"><img src="/images/newton_navigation_cover.png" width="300" alt="Quadruped navigation in Newton simulation"></video> | Physics simulation. |
| **MuJoCo** | <video width="300" style="max-width:100%;height:auto;" autoplay muted loop playsinline preload="metadata" poster="/images/mujoco_navigation_cover.png" aria-label="Quadruped navigation in MuJoCo simulation"><source src="/images/mujoco_navigation_loop.mp4" type="video/mp4"><img src="/images/mujoco_navigation_cover.png" width="300" alt="Quadruped navigation in MuJoCo simulation"></video> | Physics simulation. |
| **mjlab** | <video width="300" style="max-width:100%;height:auto;" autoplay muted loop playsinline preload="metadata" poster="/images/mjlab_go2_simulation_cover.png" aria-label="Unitree Go2 locomotion in mjlab simulation"><source src="/images/mjlab_go2_simulation.mp4" type="video/mp4"><img src="/images/mjlab_go2_simulation_cover.png" width="300" alt="Unitree Go2 in mjlab simulation"></video> | Unitree Go2 locomotion simulation using mjlab and MuJoCo Warp. |
| **Custom Terrains** | <img src="/images/terrian.png" width="300"/> | Procedurally generated terrains for testing locomotion, stability, and adaptive control. |
| **Self-design Simulation** | <video width="300" style="max-width:100%;height:auto;" autoplay muted loop playsinline preload="metadata" poster="/images/dromos_simulation_cover.png" aria-label="Multi-goal motion planning simulation"><source src="/images/dromos_simulation_loop.mp4" type="video/mp4"><img src="/images/dromos_simulation_cover.png" width="300" alt="Multi-goal motion planning simulation"></video> | self-design simulation using C++ for motion planning or multi-goal motion planning. |

