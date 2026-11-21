<a href="https://githaewon.github.io/portfolio-lab/"><img src="assets/site-qr.png" align="right" width="120" alt="포트폴리오 사이트 바로가기 QR 코드"></a>

**🔗 사이트 바로가기 → [githaewon.github.io/portfolio-lab](https://githaewon.github.io/portfolio-lab/)**

# Physical AI Portfolio

**박해원 · Physical AI Engineer**
전주대학교 인공지능학과 · 이동 로봇 · 강화학습 · 멀티에이전트

> 스스로 판단하고 함께 움직이는 이동 로봇을 탐구합니다.

현장에서 일하는 이동 로봇이 어떻게 스스로 판단하고, 여러 대가 어떻게 함께 일할 수 있는지를 연구하는 Physical AI 포트폴리오 사이트입니다. 카메라와 LiDAR로 주변을 이해하는 인식, 시행착오로 행동을 배우는 강화학습, 여러 로봇이 일을 나누는 멀티에이전트 협업을 스마트 팩토리·물류 시뮬레이션에서 직접 실험한 기록을 담았습니다.

<br clear="right">

## 연구 관심

| 단계 | 주제 | 탐색 질문 |
| --- | --- | --- |
| **Perception** | 주변을 이해하는 로봇 | 센서 정보가 불완전할 때, 로봇은 주변을 얼마나 믿고 움직여도 될까? |
| **Reinforcement Learning** | 스스로 판단하는 로봇 | 학습한 판단이 처음 보는 상황에서도 안전하게 작동하려면 무엇이 필요할까? |
| **Multi-agent** | 함께 일하는 로봇 | 로봇이 늘어날수록 생기는 충돌과 대기를 어떻게 줄일 수 있을까? |

## 프로젝트

| 기간 | 프로젝트 | 내용 | 상태 |
| --- | --- | --- | --- |
| 2026.07 | [Industrial Sim Capstone](https://githaewon.github.io/portfolio-lab/projects/industrial-sim-capstone.html) | 컨베이어 · RGB-D 비전 인식 · 로봇팔 Pick & Place · Nav2 AMR 운송을 하나의 ROS 2 공정 상태 머신으로 통합 | 개인 · 완료 |
| 2026.11 ~ | [Physical AI 멀티 로봇 주행](https://githaewon.github.io/portfolio-lab/projects/physical-ai-mobility.html) | 차량형 로봇의 이동 장애물 회피를 강화학습(PPO)으로 학습하고 MPPI와 비교, 다중 로봇 협업 주행으로 확장 | 개인 · 진행 중 |
| 2026.11 ~ | [Smart APC](https://githaewon.github.io/portfolio-lab/projects/smart-apple-apc.html) | 카메라 사과 등급 판정 → AMR 등급별 운반. AMR 주행 · 물류(Nav2) 파트 담당 | 팀 · 진행 중 |
| 2026.11 ~ | [전주대 도서관 책등 OCR](https://githaewon.github.io/portfolio-lab/projects/jj-library-ocr.html) | YOLO11n 청구기호 라벨 검출 + PP-OCRv5 인식 장서점검 데모. YOLO + OCR 담당 | 6인 팀 · 진행 중 |

## 기술 스택

- **Robotics & Simulation** — ROS 2, Gazebo, Nav2 · AMCL, RViz2, MuJoCo, State Machine Design
- **Learning & Control** — 강화학습(PPO), MPPI, 멀티에이전트 협업
- **Computer Vision** — OpenCV, YOLO11n, PP-OCRv5, EasyOCR, RGB-D 위치 추정

## 사이트 구성

| 경로 | 내용 |
| --- | --- |
| `index.html` | 메인 — Profile · Research · Projects · Skills · Activities · Awards |
| `projects/` | 프로젝트별 상세 페이지 |
| `certificates.html` | 이수증 (Microsoft × SKKU Agenthon, 전주대 ND1 피지컬 AI, THU × AICOSS 등) |
| `licenses.html` | 자격증 |
| `assets/` | 스타일(`mono.css`), 스크립트(`app.js`), 프로젝트 이미지 · 영상 |
| `lab.html`, `demo-01/`, `demo-02/` | 초기 연습용 데모 (보관용) |

## 로컬 확인 · 배포

```bash
git clone https://github.com/GitHaewon/portfolio-lab.git
cd portfolio-lab
python -m http.server 8000   # http://localhost:8000 에서 확인
```

`main` 브랜치에 푸시하면 GitHub Pages에 자동 반영됩니다.

## Contact

- Email — hye1119703@naver.com
- GitHub — [@GitHaewon](https://github.com/GitHaewon)
