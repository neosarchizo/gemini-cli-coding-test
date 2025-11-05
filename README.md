# gemini-cli-coding-test

`Gemini CLI`를 활용해 코딩 테스트를 풀 수 있도록 명령어 추가

## Browser MCP

`Chrome`에 [Browser MCP](https://chromewebstore.google.com/detail/browser-mcp-automate-your/bjfgambnhccakkhmkepdoekmckoijdlc)를 설치해야 명령어를 실행할 수 있음

## 사용방법

- `Chrome`에서 코딩 테스트 페이지로 이동
- `Chrome`의 `Brower MCP` 확장 프로그램에서 `연결` 버튼 클릭
- 명령어 사용

## 명령어

### /get-test [문제 URL]

문제 제목 이름으로 폴더를 생성하고, 그 안에 `test.md` 파일에 문제를 정리

### /analyze-test [문제 파일 경로]

문제를 분석한 뒤 같은 폴더에 `analyze.md` 파일 생성

### /solve-test [문제 파일 경로]

문제를 풀어서 같은 폴더에 `solution.py` 파일 생성
