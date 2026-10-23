냥구간 웹앱

1) 가장 간단한 확인
- index.html을 더블클릭해서 Chrome/Safari로 엽니다.
- 사료/모래/소모품 입력과 기록, 사진, 백업 기능이 브라우저에서 작동합니다.

2) iPhone에서 앱처럼 사용하려면
- 이 폴더를 HTTPS 웹호스팅에 올린 뒤 Safari로 접속합니다.
- Safari 공유 버튼 > 홈 화면에 추가.
- 서비스워커(PWA)는 file://로 직접 열 때는 동작하지 않고, HTTPS 또는 localhost에서 동작합니다.

3) 회사 Mac에서 서버로 확인(선택)
macOS에 기본 Python이 있다면 터미널에서 이 폴더로 이동 후:
python3 -m http.server 8080
그 뒤 http://localhost:8080 을 브라우저에서 엽니다.

데이터
- 브라우저 localStorage에 저장됩니다.
- 브라우저 데이터 삭제에 대비해 '기록 > 백업 저장'을 사용하세요.
