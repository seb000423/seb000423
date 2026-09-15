<!--
==============================================================================
 GitHub Profile README  (repo: seb000423/seb000423  →  파일명 README.md)
------------------------------------------------------------------------------
 사용한 generator
  1. capsule-render  https://github.com/kyechan99/capsule-render   → 맨 위 물결 헤더
  2. shields.io      https://shields.io                            → 기술스택·연락처 배지
                     (로고 이름은 https://simpleicons.org 에서 검색)
  3. 나머지는 순수 Markdown. GitHub은 style 속성을 지우므로 <h2 style="..."> 대신
     그냥 ## 를 씁니다. 결과는 동일하고 소스가 훨씬 깔끔합니다.
  (선택) github-readme-stats → 맨 아래 주석 처리해 둠
------------------------------------------------------------------------------
 대괄호 [ ] 부분만 채우고, 안 쓰는 줄은 지우면 됩니다.
==============================================================================
-->

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=240&text=%F0%9F%91%8B%20Hello%2C%20I'm%20Boo%20Seung%20Eon&animation=fadeIn&fontColor=ffffff&fontSize=42&desc=Robot%20Manipulation%20%C2%B7%20Imitation%20Learning%20%C2%B7%20Reinforcement%20Learning&descSize=17&descAlignY=62" />
</div>

## AI · Robotics Engineer — Robot Manipulation

로봇팔이 사람의 손작업을 대신하도록 학습 기반 제어를 만듭니다.
시연 데이터로 동작을 학습하고(BC), 강화학습으로 다듬으며(PPO),
공정 파라미터는 베이지안 최적화로 찾습니다.

---

## 🛠️ Tech Stacks

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=plastic&logo=Python&logoColor=white">
  <img src="https://img.shields.io/badge/ROS-22314E?style=plastic&logo=ROS&logoColor=white">
  <img src="https://img.shields.io/badge/Isaac%20Sim-76B900?style=plastic&logo=NVIDIA&logoColor=white">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=plastic&logo=PyTorch&logoColor=white">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=plastic&logo=OpenCV&logoColor=white">
</div>

---

## 🚀 Projects

<!--
  작성 규칙: 제목 → 한 줄 요약 → 무엇을 했는지 → 결과(수치) → 기술스택 → 링크.
  "무엇을 썼는가"보다 "무엇이 좋아졌는가"를 먼저. 수치가 없으면 비교 대상이라도 쓰세요.
-->

### cacadaca — 로봇팔 기반 차체 표면 가공 자동화

사람이 손으로 하던 차체 연마(폴리싱·샌딩·디버링)를 로봇팔이 수행하도록 만드는 프로젝트.

- **BO** — 공정 레시피(압력·속도·경로 파라미터) 탐색
- **BC** — 숙련 작업자의 시연 데이터로 동작 정책 학습
- **PPO** — 학습된 정책의 미세 보정
- **Result:** [정량 결과 — 예: 표면 조도 Ra [x] → [y], 사이클 타임 [z]% 단축]
- **Stack:** Python, PyTorch, ROS, Isaac Sim
- **Repo:** [seb000423/cacadaca](https://github.com/seb000423/cacadaca)

### [프로젝트 2 제목]

[한 줄 요약 — 어떤 문제를 풀었는지.]

- [무엇을 했는지 1]
- [무엇을 했는지 2]
- **Result:** [수치로 표현된 결과]
- **Stack:** [사용 기술]
- **Repo:** [[repo 이름]](https://github.com/seb000423/[repo])

---

## 🎓 Education & Training

<!--
  기관명을 ### 소제목으로 올리면 글자가 커져서 가장 강하게 강조됩니다.
  ① 기간과 총 교육시간을 함께 (예: 2025.03 ~ 2025.09 · 960h)
  ② "배웠다"가 아니라 "만들었다" — 산출물 레포 링크가 수료증보다 강함
  ③ 수료증 PDF는 이 레포 /certs 폴더에 올리고 링크, 검증 URL이 있으면 그걸 우선
  ④ 산출물 없는 수료증·자격증은 아래 표로 몰아서 정리
-->

### 두산로보틱스 · ROKEY BOOT CAMP

**AI·로봇 엔지니어 양성과정 [N]기** *([YYYY.MM] ~ [YYYY.MM] · [총 교육시간]h)*

협동로봇 · 컴퓨터비전 · 모바일 매니퓰레이터 · 디지털트윈을 다루는 ROS 기반 과정
(기술이론 4개월 + 실무 프로젝트 2개월)

- **What I built:** [실무 프로젝트 1줄 요약] → [Repo](https://github.com/seb000423/[repo])
- **Stack:** ROS 2, Python, [OpenCV, PyTorch, Doosan M/H-series, ...]
- **Certificate:** [수료증](./certs/rokey.pdf) <!-- 없으면 삭제 -->

### [대학교]

**[학위], [전공]** *([YYYY.MM] ~ [YYYY.MM 또는 Present])*

<!-- 학력을 넣지 않으려면 이 ### 블록 전체를 삭제하세요 -->

**Certifications**

| Credential | Issuer | Date | Verify |
|---|---|---|---|
| [자격증·수료증 이름] | [발급기관] | [YYYY.MM] | [Link](#) |
| [자격증·수료증 이름] | [발급기관] | [YYYY.MM] | [Link](#) |

---

## 🏅 Awards

<!--
  수상은 최신순. 정부 시상(장관상·국무총리상)은 가장 강한 항목이라 맨 위에 둡니다.
  대회는 회차를 포함한 공식 명칭으로, 주최/주관 기관까지 적으면 검증 가능해 보입니다.
-->

| Award | Host | Date |
|---|---|---|
| **제8회 K-디지털 트레이닝 해커톤 — 최우수상 (고용노동부 장관상)** | 고용노동부 주최 · 한국기술교육대학교 직업능력심사평가원 주관 | 2026.09 |
| LINC 3.0 캡스톤디자인 경진대회 — 우수상 | LINC 3.0 사업단 | 2024 |

---

## 📫 Contact

<div align="center">
  <a href="mailto:seb000423@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=plastic&logo=Gmail&logoColor=white"></a>
  <a href="https://github.com/seb000423"><img src="https://img.shields.io/badge/GitHub-181717?style=plastic&logo=GitHub&logoColor=white"></a>
</div>

<!--
  ▼ GitHub 통계 카드. 쓰려면 이 주석 블록의 첫 줄과 마지막 줄만 지우세요.
  theme 예시: tokyonight, dark, radical, gruvbox, github_dark

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=seb000423&show_icons=true&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=seb000423&layout=compact&theme=tokyonight)

</div>
-->
