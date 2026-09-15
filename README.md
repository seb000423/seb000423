<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=210&text=%F0%9F%91%8B%20Hello%2C%20I'm%20Seungeon%20Boo&animation=fadeIn&fontColor=ffffff&fontSize=38&desc=Physical%20AI%20%C2%B7%20Robot%20Digital%20Twin%20%C2%B7%20Sim-to-Real&descSize=15&descAlignY=62" />
</div>

## AI · Robotics Engineer — Robot Arm Manipulation & Digital Twin

I specialize in teaching **robot arms** the manual work people do by hand, particularly contact-rich tasks such as polishing, sanding and deburring that are difficult to program explicitly. My approach starts in simulation: I build the digital twin of the full robot cell — the arms together with their linear rail, telescopic lift and workpiece fixtures — then train a policy there from human demonstrations and the policy's own rollouts, and transfer it to the physical manipulator. Currently I am building **cacadaca**, an end-to-end pipeline that turns a skilled operator's surface finishing work into a robot arm policy.

**Focus**

- Manipulation with Robot Arms — Contact-Rich Tasks
- Multi-Robot Cells with External Axes — Linear Rail, Telescopic Lift
- Imitation & Reinforcement Learning from Demonstrations and Simulated Rollouts
- Robot Simulation & Digital Twin — NVIDIA Isaac Sim
- Sim-to-Real Transfer

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

### 🚀 Projects

#### cacadaca — Robotic Surface Finishing for Car Bodies

Automating car-body finishing (polishing, sanding, deburring) that has been done by hand.

- **Cell** — modeled the whole workcell in Isaac Sim: robot arms on a linear rail with a telescopic lift, workpiece fixtures and contact setup, driven as one extended kinematic chain
- **Coordination** — coordinated multiple arms in the same cell and tied each arm's reachable workspace to the current lift pose, keeping motions within reach and collision-free
- **BO** — searches the process recipe (pressure, speed, path parameters)
- **BC** — learns the motion policy from skilled operators' demonstrations
- **PPO** — fine-tunes the learned policy
- **Result:** [정량 결과 — 예: surface roughness Ra [x] → [y], cycle time reduced by [z]%]
- **Stack:** Python, PyTorch, ROS, Isaac Sim
- **Repo:** [seb000423/cacadaca](https://github.com/seb000423/cacadaca)

#### [Project 2 Title]

[한 줄 요약 — what problem it solves.]

- [무엇을 했는지 1]
- [무엇을 했는지 2]
- **Result:** [수치로 표현된 결과]
- **Stack:** [사용 기술]
- **Repo:** [[repo name]](https://github.com/seb000423/[repo])

---

### 🎓 Education & Training

#### Doosan Robotics · ROKEY BOOT CAMP

**AI & Robotics Engineer Program, Cohort [N]** *([YYYY.MM] – [YYYY.MM] · [총 교육시간]h)*

- Collaborative robots, computer vision, mobile manipulators, and digital twin — ROS-based (4 months coursework + 2 months industry project)
- **What I built:** [실무 프로젝트 1줄 요약] → [Repo](https://github.com/seb000423/[repo])
- **Stack:** ROS 2, Python, [OpenCV, PyTorch, Doosan M/H-series, ...]
- **Certificate:** [Certificate](./certs/rokey.pdf)

#### [University]

**[Degree], [Major]** *([YYYY.MM] – [YYYY.MM 또는 Present])*

---

### 🏅 Awards

| Award | Host | Date |
|---|---|---|
| **8th K-Digital Training Hackathon — First Prize (Minister of Employment and Labor Award)** | Ministry of Employment and Labor · KOREATECH | 2026.09 |
| LINC 3.0 Capstone Design Competition — Excellence Award | LINC 3.0 Project Group | 2024 |

---

### 📜 Certifications

| Credential | Issuer | Date | Verify |
|---|---|---|---|
| [자격증·수료증 이름] | [발급기관] | [YYYY.MM] | [Link](#) |
| [자격증·수료증 이름] | [발급기관] | [YYYY.MM] | [Link](#) |
