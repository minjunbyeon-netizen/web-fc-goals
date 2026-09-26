# web-fc-goals — FC Online 골 모음 공개 페이지

- 정적 HTML 1장(`index.html`). GitHub Pages 로 공개: https://minjunbyeon-netizen.github.io/web-fc-goals/
- 생성기는 dev-root `C:\dev\game\medal_pick.py` (Medal 로컬 DB 에서 골/실점 클립을 골라 medal.tv 링크 목록 생성).
  갱신: `python C:\dev\game\medal_pick.py --days 09-24:5,09-25:7,09-26:7 --public --out C:\dev\web\fc-goals` 후 commit+push
- 이 repo 는 공개(public). 로컬 경로·개인정보 넣지 않는다. `--public` 없이 만든 파일(로컬 `file:///` 링크 포함)은 올리지 않는다.
- 환경변수·서버 없음(.env 불필요).
