# JuWonpage
- [홈페이지 주소](https://juwonk-bme.netlify.app/)


---
업데이트 하는 법
1. docs폴더에 파일 넣기
2. R srtudio에서 render해서 _site 폴더에 .html파일 생성시키기
3. cmd 창에서 아래 명령어 입력하기
  - git add .
  - git commit -m "message"
  - git push origin main
    - 에러
    - [reject !] error: failed to push some refs to ~ 이러한 에러 발생시
        -git push origin +main으로 해보기
    - 방법 2) git pull -> git init 한 후 위 명령어 입력
