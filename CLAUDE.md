# web-fc-goals — FC Online 골 모음 공개 페이지

- 정적 사이트(`index.html` + `clips/*.mp4`). GitHub Pages 로 공개: https://minjunbyeon-netizen.github.io/web-fc-goals/
- 생성기는 dev-root `C:\dev\game\medal_pick.py` (Medal 로컬 DB 에서 골/실점 클립을 골라 ffmpeg 로 줄여 넣음).
  갱신: `python C:\dev\game\medal_pick.py --days 09-24:5,09-25:7,09-26:9 --encode --out C:\dev\web\fc-goals` 후 commit+push
  (이미 있는 clips/ 파일은 건너뛴다. 목록에서 빠진 클립 파일은 손으로 지운다.)
- 클립은 720p 30fps crf28, 오디오는 게임 소리 트랙만(Discord 음성 트랙 제외).
- 이 repo 는 공개(public). 로컬 경로·개인정보 넣지 않는다. `--public`/`--encode` 없이 만든 파일(로컬 `file:///` 링크 포함)은 올리지 않는다.
- 환경변수·서버 없음(.env 불필요).
