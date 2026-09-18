<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,55:0A0A0A,100:76B900&height=210&text=%F0%9F%91%8B%20Hello%2C%20I'm%20Seungeon%20Boo&animation=fadeIn&fontColor=ffffff&fontSize=38&desc=Physical%20AI%20%C2%B7%20Robot%20Digital%20Twin%20%C2%B7%20Sim-to-Real&descSize=15&descAlignY=62" />
</div>

## AI · Robotics Engineer — Robot Digital Twin & Sim-to-Real

I work on robot digital twins and sim-to-real transfer. I build simulation environments for robots and train policies there on expert demonstration data through behavior cloning, then refine them with reinforcement learning. My current focus is manipulation: contact-rich tasks such as polishing, sanding and deburring that are difficult to program explicitly.

## 🛠️ Tech Stacks

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=plastic&logo=Python&logoColor=white">
  <img src="https://img.shields.io/badge/ROS-22314E?style=plastic&logo=ROS&logoColor=white">
  <img src="https://img.shields.io/badge/Isaac%20Sim-76B900?style=plastic&logo=NVIDIA&logoColor=white">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=plastic&logo=PyTorch&logoColor=white">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=plastic&logo=OpenCV&logoColor=white">
</div>

## 🧑‍💻 Contact

<div align="center">
  <a href="mailto:seb000423@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=plastic&logo=Gmail&logoColor=white"></a>
  <a href="https://github.com/seb000423"><img src="https://img.shields.io/badge/GitHub-181717?style=plastic&logo=GitHub&logoColor=white"></a>
</div>

---

### 🔭 Interests

- Physical AI & Robot Digital Twin
- Sim-to-Real Transfer
- Imitation Learning & Reinforcement Learning
- Contact-Rich Manipulation
- Multi-Arm Coordination with External Axes
- Virtual Commissioning for Autonomous Manufacturing

---

### 🚀 Projects

- **[Robotic Surface Finishing Digital Twin](https://github.com/seb000423/robotic-surface-finishing-digital-twin)**
  - Automating surface finishing (polishing, sanding, deburring) that has been done by hand, with a digital twin of the workcell.
  - **Cell:** modeled the whole workcell in Isaac Sim — robot arms on a linear rail with a telescopic lift, workpiece fixtures and contact setup, driven as one extended kinematic chain
  - **Coordination:** coordinated multiple arms in the same cell and tied each arm's reachable workspace to the current lift pose, keeping motions within reach and collision-free
  - **BO:** searches the process recipe (pressure, speed, path parameters)
  - **BC:** learns the motion policy from expert demonstration data
  - **PPO:** refines the learned policy
  - **Tech:** Python, PyTorch, ROS, Isaac Sim

- **[Seek6D](https://github.com/seb000423/Seek6D)**
  - ROS 2 cobot pipeline that finds a requested object on its own — voice command, active search, opening drawers to re-observe, then grasping.
  - **Perception:** GroundingDINO detection and Any6D 6D pose estimation, with multi-stage pose validation
  - **Manipulation:** collision-aware grasping with MoveIt 2 on a Doosan M0609
  - **Tech:** ROS 2, Python, MoveIt 2, GroundingDINO, Any6D

- **[Dish Washing Cobot](https://github.com/seb000423/Dish_Washing_Cobot)**
  - Washes plates, bowls and cups by contact, using a cobot instead of a spray-based dishwasher.
  - **Motion:** shape-specific washing trajectories with force/compliance control and re-grasping for occluded regions
  - **Interface:** ROS 2 task orchestration with a physical button and a Flask web UI
  - **Tech:** ROS 2, Python, Doosan M0609, OnRobot RG2, Flask
