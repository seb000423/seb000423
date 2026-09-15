<!--
==============================================================================
 GitHub Profile README  (repo: seb000423/seb000423  →  파일명 README.md)
------------------------------------------------------------------------------
 사용한 generator
  1. capsule-render  https://github.com/kyechan99/capsule-render   → 맨 위 물결 헤더
  2. shields.io      https://shields.io                            → 기술스택·연락처 배지
                     (로고 이름은 https://simpleicons.org 에서 검색)
  3. 나머지는 순수 Markdown.

 제목 위계 (이것만 지키면 전체 톤이 흐트러지지 않습니다)
  ##   → 타이틀 / Tech Stacks / Contact  (상단 3개만)
  ###  → 구분선 아래 이력 섹션 전부
  #### → 개별 항목명 (기관명·프로젝트명)
 정렬: 본문은 왼쪽, 배지만 <div align="center">
------------------------------------------------------------------------------
 대괄호 [ ] 부분만 채우고, 안 쓰는 줄은 지우면 됩니다.
==============================================================================
-->

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=210&text=%F0%9F%91%8B%20Hello%2C%20I'm%20Seungeon%20Boo&animation=fadeIn&fontColor=ffffff&fontSize=38&desc=Physical%20AI%20%C2%B7%20Robot%20Digital%20Twin%20%C2%B7%20Sim-to-Real&descSize=15&descAlignY=62" />
</div>

## AI · Robotics Engineer — Physical AI & Robot Digital Twin

I build robots that learn manual work from data. I set up simulation environments, generate the data policies need, train them there, and bring them back to the real robot arm.

**Focus**

- Robot Simulation & Digital Twin — NVIDIA Isaac Sim
- Imitation Learning & Reinforcement Learning for Manipulation
- Training Data from Demonstrations & Simulated Rollouts
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

<!-- 작성 규칙: 제목 → 한 줄 요약 → 무엇을 했는지 → 결과(수치) → 기술스택 → 링크 -->

#### cacadaca — Robotic Surface Finishing for Car Bodies

Automating car-body finishing (polishing, sanding, deburring) that has been done by hand.

- **Sim** — built the Isaac Sim cell (robot, workpiece, contact setup) used to generate training data
- **BO** — searches the process recipe (pressure, speed, path parameters)
- **BC** — learns the motion policy from skilled operators' demonstrations
- **PPO** — fine-tunes the learned policy
- **Result:** [정량 결과 — 예: surface roughness Ra [x] → [y], cycle time reduced by [z]%]
- **Stack:** Python, PyTorch, ROS, Isaac Sim
- **Repo:** [seb000423/cacadaca](https://github.com/seb000423/cacadaca)

#### [Project 2 Title]

<!-- 지원 포지션(로봇 디지털트윈)을 노린다면: 시뮬레이션 환경 구축, 합성데이터 생성 파이프라인,
     Virtual Commissioning 검증 중 하나를 2번 프로젝트로 올리는 게 가장 효과적입니다.
     부트캠프 실무 프로젝트가 여기에 해당하면 그걸 올리세요. -->

[한 줄 요약 — what problem it solves.]

- [무엇을 했는지 1]
- [무엇을 했는지 2]
- **Result:** [수치로 표현된 결과]
- **Stack:** [사용 기술]
- **Repo:** [[repo name]](https://github.com/seb000423/[repo])

---

### 🎓 Education & Training

<!--
  ① 기간과 총 교육시간을 함께 (예: 2025.03 – 2025.09 · 960h)
  ② "배웠다"가 아니라 "만들었다" — 산출물 레포 링크가 수료증보다 강함
  ③ 수료증 PDF는 이 레포 /certs 폴더에 올리고 링크, 검증 URL이 있으면 그걸 우선
-->

#### Doosan Robotics · ROKEY BOOT CAMP

**AI & Robotics Engineer Program, Cohort [N]** *([YYYY.MM] – [YYYY.MM] · [총 교육시간]h)*

- Collaborative robots, computer vision, mobile manipulators, and digital twin — ROS-based (4 months coursework + 2 months industry project)
- **What I built:** [실무 프로젝트 1줄 요약] → [Repo](https://github.com/seb000423/[repo])
- **Stack:** ROS 2, Python, [OpenCV, PyTorch, Doosan M/H-series, ...]
- **Certificate:** [Certificate](./certs/rokey.pdf) <!-- 없으면 삭제 -->

#### [University]

**[Degree], [Major]** *([YYYY.MM] – [YYYY.MM 또는 Present])*

<!-- 학력을 넣지 않으려면 이 #### 블록 전체를 삭제하세요 -->

---

### 🏅 Awards

| Award | Host | Date |
|---|---|---|
| **8th K-Digital Training Hackathon — First Prize (Minister of Employment and Labor Award)** | Ministry of Employment and Labor · KOREATECH | 2026.09 |
| LINC 3.0 Capstone Design Competition — Excellence Award | LINC 3.0 Project Group | 2024 |

---

### 📜 Certifications

<!-- 산출물 없는 수료증·자격증은 여기에 표로. 없으면 이 섹션째 삭제 -->

| Credential | Issuer | Date | Verify |
|---|---|---|---|
| [자격증·수료증 이름] | [발급기관] | [YYYY.MM] | [Link](#) |
| [자격증·수료증 이름] | [발급기관] | [YYYY.MM] | [Link](#) |

<!--
  ▼ GitHub 통계 카드. 쓰려면 이 주석 블록의 첫 줄과 마지막 줄만 지우세요.
  theme 예시: tokyonight, dark, radical, gruvbox, github_dark

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=seb000423&show_icons=true&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=seb000423&layout=compact&theme=tokyonight)

</div>
-->
