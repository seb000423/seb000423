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

- **Robotic Surface Finishing for Car Bodies**
  - Automating car-body finishing (polishing, sanding, deburring) that has been done by hand.
  - **Cell:** modeled the whole workcell in Isaac Sim — robot arms on a linear rail with a telescopic lift, workpiece fixtures and contact setup, driven as one extended kinematic chain
  - **Coordination:** coordinated multiple arms in the same cell and tied each arm's reachable workspace to the current lift pose, keeping motions within reach and collision-free
  - **BO:** searches the process recipe (pressure, speed, path parameters)
  - **BC:** learns the motion policy from expert demonstration data
  - **PPO:** refines the learned policy
  - **Result:** [정량 결과 — 예: in simulation, surface roughness Ra [x] → [y], success rate [z]%]
  - **Tech:** Python, PyTorch, ROS, Isaac Sim

- **[Project 2 Title]**
  - [한 줄 요약 — what problem it solves.]
  - [무엇을 했는지]
  - **Result:** [수치로 표현된 결과]
  - **Tech:** [사용 기술]
