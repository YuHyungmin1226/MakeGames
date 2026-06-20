# Modern Neon Games Collection - 레트로 게임 컬렉션

클래식 아케이드 게임 5종을 현대적인 **사이버펑크/네온** 감성으로 재해석한 웹 게임 컬렉션입니다. 각 게임은 모든 로직, 스타일링, 오디오 합성을 포함한 단독 HTML 파일로 구성되어 있습니다.

## 게임 목록

### 1. Neon Brick Breaker (`Modern Brick Breaker.html`)
물리 기반 공 반사 각도, 다이내믹 파티클 폭발, 절차적 사운드 효과가 적용된 벽돌깨기 게임입니다.

### 2. Neon Pong (`Modern Pong.html`)
AI CPU를 상대하는 1:1 라켓 게임입니다. 글로우 트레일, 충돌 효과, 글래스모피즘 UI를 지원합니다.

### 3. Neon Tetris (`Modern Tetris.html`)
회전 및 벽킥 메커니즘, 하드/소프트 드롭, 타임어택 모드를 지원하는 빠른 퍼즐 게임입니다.

### 4. Neon Match 3 (`Modern Match 3.html`)
60초 타임어택 방식의 매치3 퍼즐입니다. 중력 및 연쇄 콤보 시스템, 코드 기반 오디오 피드백을 제공합니다.

### 5. Neon Snake (`Modern Snake.html`)
입력 버퍼링 기반의 부드러운 그리드 이동, 먹이 섭취 시 속도 증가, 화면 효과가 적용된 스네이크 게임입니다.

## 기술 스택

- **Core**: HTML5 Canvas + Vanilla JavaScript
- **스타일링**: Tailwind CSS (CDN)
- **오디오**: Web Audio API (외부 에셋 없음, 실시간 합성)
- **디자인**: CSS 그림자와 합성 연산을 사용한 커스텀 네온/글래스모피즘 테마

## 실행 방법

별도의 설치나 서버가 필요하지 않습니다. 각 `.html` 파일을 브라우저(Chrome/Edge/Firefox 권장)에서 더블클릭하여 바로 실행할 수 있습니다.

```bash
# 저장소 클론
git clone https://github.com/YuHyungmin1226/MakeGames.git
# 폴더로 이동 후 원하는 HTML 파일을 브라우저로 열기
```

## 라이선스

MIT License
