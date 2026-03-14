# 👾 바이브 코딩 레트로 게임 모음

> 📖 **«코딩 몰라도 OK! 바이브 코딩으로 레트로 게임 만들기»** 전자책의 예제 게임 모음입니다.
> AI 프롬프트만으로 만든 HTML/JavaScript 게임 5종을 브라우저에서 바로 플레이할 수 있습니다.

🎮 **[▶ 지금 바로 플레이하기](https://y-ahn.github.io/retro-games/)**

---

## 🕹️ 게임 목록

| 게임 | 난이도 | 바로 플레이 |
|------|--------|------------|
| 🐍 뱀 게임 (Snake) | ⭐☆☆☆☆ 입문 | [플레이](https://y-ahn.github.io/retro-games/snake.html) |
| 🧱 벽돌깨기 (Breakout) | ⭐⭐☆☆☆ 초급 | [플레이](https://y-ahn.github.io/retro-games/breakout.html) |
| 🟦 테트리스 (Tetris) | ⭐⭐⭐☆☆ 중급 | [플레이](https://y-ahn.github.io/retro-games/tetris.html) |
| 🟡 팩맨 (Pac-Man) | ⭐⭐⭐⭐☆ 고급 | [플레이](https://y-ahn.github.io/retro-games/pacman.html) |
| 🚀 스페이스 슈터 | ⭐⭐⭐⭐⭐ 고난이도 | [플레이](https://y-ahn.github.io/retro-games/space-shooter.html) |

---

## 🚀 게임 기능 요약

### 🐍 뱀 게임
- 방향키 / WASD 조작
- 레벨 시스템 (점수에 따라 속도 증가)
- 최고 점수 표시
- Web Audio 효과음

### 🧱 벽돌깨기
- 마우스 또는 방향키 조작
- 색상별 점수 차등 (빨강 30점 ~ 하늘 5점)
- 강철 벽돌 (2회 타격)
- 파워업 아이템 (패들 확장, 슬로우)
- 멀티 스테이지

### 🟦 테트리스
- 7가지 테트로미노 (정규 색상)
- 고스트 피스
- 홀드 기능 (C / Shift)
- 다음 블록 미리보기
- 레벨업 & 속도 증가

### 🟡 팩맨
- 타일 기반 미로
- 4마리 유령 AI (Blinky, Pinky, Inky, Clyde)
- Power Pellet → 유령 포획 가능
- 연속 처치 콤보 점수

### 🚀 스페이스 슈터
- 편대 이동 외계인
- 5웨이브마다 보스 등장 (3단계 탄막 패턴)
- 파워업 아이템 (멀티샷, 방어막, 폭탄)
- 별이 흐르는 스크롤 배경
- 모바일 터치 지원

---

## 📂 파일 구조

```
retro-games/
├── index.html          ← 메인 허브 페이지
├── snake.html          ← 뱀 게임
├── breakout.html       ← 벽돌깨기
├── tetris.html         ← 테트리스
├── pacman.html         ← 팩맨
├── space-shooter.html  ← 스페이스 슈터
└── README.md
```

---

## 🛠️ GitHub Pages 배포 방법

1. 이 저장소를 **Fork** 하거나 직접 파일을 업로드합니다.
2. **Settings** → **Pages** → **Source: main branch** 선택 후 **Save**
3. 잠시 후 `https://[내계정].github.io/retro-games/` 에서 플레이 가능!

---

## 💡 이 게임들은 어떻게 만들었나요?

모든 게임은 **Claude AI**에게 프롬프트를 입력해서 만들었습니다.  
코딩 지식 없이도 AI와 대화만으로 완성한 게임들입니다.

사용 예시:
```
레트로 픽셀 스타일의 뱀 게임을 HTML과 JavaScript로 만들어줘.
방향키로 조작하고, 먹이를 먹으면 길어지고 점수가 오르고,
벽이나 자기 몸에 닿으면 게임 오버가 되게 해줘.
배경은 검정, 뱀은 초록색, 한 개의 HTML 파일로 완성해줘.
```

---

## 📖 관련 전자책

**«바이브 코딩 시리즈 2 코딩 몰라도 OK! 바이브 코딩으로 레트로 게임 만들기»**

- 각 게임별 단계별 프롬프트 가이드
- 커스터마이징 방법
- 배포 및 공유 방법

---

*Made with ❤️ using AI Vibe Coding — No code knowledge required!*
