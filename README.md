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
  <img src="https://img.shields.io/badge/C++-00599C?style=plastic&logo=C%2B%2B&logoColor=white">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=plastic&logo=PyTorch&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-013243?style=plastic&logo=NumPy&logoColor=white">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=plastic&logo=OpenCV&logoColor=white">
  <br/>
  <img src="https://img.shields.io/badge/ROS-22314E?style=plastic&logo=ROS&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=plastic&logo=Docker&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=plastic&logo=Linux&logoColor=black">
  <img src="https://img.shields.io/badge/Git-F05032?style=plastic&logo=Git&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=plastic&logo=GitHub&logoColor=white">
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
- **Stack:** Python, PyTorch, ROS, [시뮬레이터명]
- **Repo:** [seb000423/cacadaca](https://github.com/seb000423/cacadaca)

### [프로젝트 2 제목]

[한 줄 요약 — 어떤 문제를 풀었는지.]

- [무엇을 했는지 1]
- [무엇을 했는지 2]
- **Result:** [수치로 표현된 결과]
- **Stack:** [사용 기술]
- **Repo:** [[repo 이름]](https://github.com/seb000423/[repo])

---

## 🎓 Education

- **[학위], [전공]** — [대학교] *([YYYY.MM] ~ [YYYY.MM 또는 Present])*
  - **Thesis:** [학위논문 제목] <!-- 없으면 삭제 -->
  - **Coursework:** [주요 수강 과목 3~5개] <!-- 없으면 삭제 -->

---

## 🏫 Training & Certifications

<!--
  부트캠프 작성 규칙
  ① 학위(Education)와 반드시 분리
  ② 기간과 총 교육시간을 함께 (예: 2025.03 ~ 2025.09 · 960h)
  ③ "배웠다"가 아니라 "만들었다" — 산출물 레포 링크가 수료증보다 강함
  ④ 수료증 PDF는 이 레포 /certs 폴더에 올리고 링크, 검증 URL이 있으면 그걸 우선
  ⑤ 산출물 없는 수료증·자격증은 아래 표로 몰아서 정리
-->

**Programs**

- **ROKEY BOOT CAMP — AI·로봇 엔지니어 양성과정 [N]기** · 두산로보틱스 *([YYYY.MM] ~ [YYYY.MM] · [총 교육시간]h)*
  - 협동로봇 · 컴퓨터비전 · 모바일 매니퓰레이터 · 디지털트윈 (ROS 기반, 이론 4개월 + 실무 프로젝트 2개월)
  - **What I built:** [실무 프로젝트 1줄 요약] → [Repo](https://github.com/seb000423/[repo])
  - **Stack:** ROS 2, Python, [OpenCV, PyTorch, Doosan M/H-series, ...]
  - **Certificate:** [수료증](./certs/rokey.pdf) <!-- 없으면 삭제 -->

**Certifications**

| Credential | Issuer | Date | Verify |
|---|---|---|---|
| [자격증·수료증 이름] | [발급기관] | [YYYY.MM] | [Link](#) |
| [자격증·수료증 이름] | [발급기관] | [YYYY.MM] | [Link](#) |

---

## 🏅 Awards

| Award | Host | Date |
|---|---|---|
| [수상명] — [등급] | [주최 기관] | [YYYY.MM] |
| [수상명] — [등급] | [주최 기관] | [YYYY.MM] |

---

## 📫 Contact

<div align="center">
  <a href="mailto:seb000423@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=plastic&logo=Gmail&logoColor=white"></a>
  <a href="https://github.com/seb000423"><img src="https://img.shields.io/badge/GitHub-181717?style=plastic&logo=GitHub&logoColor=white"></a>
  <a href="[LinkedIn 주소]"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=plastic&logo=LinkedIn&logoColor=white"></a>
  <a href="[Notion / 블로그 주소]"><img src="https://img.shields.io/badge/Portfolio-000000?style=plastic&logo=Notion&logoColor=white"></a>
</div>

<!--
  ▼ GitHub 통계 카드. 쓰려면 이 주석 블록의 첫 줄과 마지막 줄만 지우세요.
  theme 예시: tokyonight, dark, radical, gruvbox, github_dark

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=seb000423&show_icons=true&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=seb000423&layout=compact&theme=tokyonight)

</div>
-->
