# 🏸 스매시 마스터즈: 배드민턴 로얄 (Smash Masters: Badminton Royale)

> **웹 기반 2D 아케이드 배드민턴 액션 게임**  
> 정밀한 셔틀콕 공기역학 물리, 강력한 점프 스매시, AI 대전 및 2인 로컬 대전을 지원하는 브라우저 스포츠 게임입니다.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Web Audio API](https://img.shields.io/badge/Web_Audio_API-Procedural-success?style=for-the-badge)

---

## 🌟 주요 특징 (Features)

- **🏸 현실적인 셔틀콕 물리 (Authentic Aerodynamics)**:
  - 셔틀콕 고유의 깃털 공기 저항(속도의 제곱에 비례하는 급격한 감속)을 재현하여 순간적인 폭발력과 뚝 떨어지는 낙하 궤적을 체험할 수 있습니다.
  - 네트 상단 백색 밴드(네트 코드) 접촉 물리, 코트 경계선(In / Out) 판정 시스템 내장.
- **⚡ 화려한 구질과 타격감 (Rich Shot Variety & Juiciness)**:
  - 하이 클리어(High Lob), 헤어핀/드롭샷(Net Drop), 드라이브(Drive), 급강하 점프 스매시(Jump Smash), EX 슈퍼 스매시(Super Smash).
  - 타격 히트스톱(Freeze-frame), 화면 진동(Screen Shake), 스파크 및 속도 잔상 이펙트, 스매시 속도 레이더(km/h).
- **🤖 다채로운 게임 모드 (Game Modes)**:
  - **싱글 플레이 (vs AI)**: 쉬움(Easy), 보통(Normal), 어려움(Hard) 3단계 난이도.
  - **2인 로컬 대전 (PvP)**: 하나의 키보드로 친구와 즐기는 1 vs 1 실시간 대결.
- **👥 4가지 플레이어 로스터 (Characters)**:
  - **질풍 (Flash)**: 빠른 발과 날카로운 드롭샷 중심의 스피드형
  - **타이탄 (Titan)**: 압도적인 점프와 350km/h+ 초고속 스매시를 자랑하는 파워형
  - **에이스 (Ace)**: 공수 밸런스와 빠른 필살기 게이지 충전형
  - **닌자 (Ninja)**: 체공 시간이 길고 예리한 각도의 테크닉형
- **🎵 내장 프로시저 사운드 (Procedural Audio)**:
  - 외부 음원 파일 의존 없이 **HTML5 Web Audio API**로 실시간 합성되는 타구음, 스매시 폭발음, 심판 휘슬, 관중 환호, 신스 BGM.

---

## 🕹️ 조작 방법 (Controls)

### 1P (또는 싱글 플레이 모드)
| 동작 | 조작키 (기본) | 대체 키 |
| :--- | :--- | :--- |
| **좌우 이동** | `A` / `D` | `←` / `→` |
| **점프** | `W` | `↑` |
| **헤어핀 / 드롭** | `J` | `Z` |
| **하이 클리어** | `K` | `X` |
| **스매시 / 드라이브** | `L` | `C` |
| **스마트 샷 (자동)** | `Space` | - |
| **필살기 (SUPER)** | `U` | `V` |

### 2P (로컬 대전 모드)
| 동작 | 조작키 |
| :--- | :--- |
| **좌우 이동** | 방향키 `←` / `→` |
| **점프** | 방향키 `↑` |
| **헤어핀 / 드롭** | 넘패드 `1` 또는 `[` |
| **하이 클리어** | 넘패드 `2` 또는 `]` |
| **스매시 / 드라이브** | 넘패드 `3` 또는 `\` |
| **필살기 (SUPER)** | 넘패드 `0` 또는 `/` |

*※ 모바일 및 터치 기기, 마우스 플레이를 위한 온스크린 가상 컨트롤러도 지원합니다.*

---

## 🚀 실행 방법 (Getting Started)

별도의 Node.js나 서버 설치 없이, 웹 브라우저에서 바로 실행할 수 있습니다.

1. 저장소를 클론(Clone)하거나 다운로드합니다.
```bash
git clone https://github.com/사용자이름/저장소이름.git
```
2. `index.html` 파일을 더블 클릭하여 Chrome, Edge 등의 브라우저에서 실행합니다.

---

## 📁 프로젝트 구조 (Project Structure)

```
├── index.html       # 메인 화면 구조 및 UI 모달
├── style.css        # 글래스모피즘 네온 테마 스타일시트
├── README.md        # 프로젝트 설명 문서
├── .gitignore       # Git 제외 목록
└── js/
    ├── audio.js     # Web Audio API 사운드 신디사이저
    ├── physics.js   # 셔틀콕 공기역학 및 코트 물리
    ├── effects.js   # 파티클, 화면 진동 및 경기장 렌더러
    ├── character.js # 선수 키네마틱스 및 모션 애니메이션
    ├── ai.js        # 난이도별 배드민턴 전술 AI
    └── game.js      # 메인 게임 루프, 규칙 및 입력 제어
```

---

## 📄 라이선스 (License)

This project is licensed under the MIT License.
