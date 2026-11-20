# BIOGLOW 미션 점수판

FLL BIOGLOW 일일 캠프용 점수판입니다. 학생마다 성공한 미션 점수를 누적해서 기록하고, 전자칠판에 띄워 씁니다.

- `index.html` 파일 하나로 동작합니다. 빌드 과정이 없습니다.
- 점수는 그 기기 브라우저의 localStorage에 저장됩니다.
- 상단 로고: 저장소 맨 위에 `bioglow-logo.png` 파일을 올리면 표시됩니다. 없으면 글자 로고가 나옵니다.
- 팀 설정: 이름을 끌어 2인 1조를 만들고, 프로그램 정보와 명단을 고치며, 수업 끝에 설문 코드를 띄웁니다.
- Vercel: Add New → Project에서 이 저장소를 가져오고, Framework Preset을 `Other`로 두고 Deploy를 누르면 됩니다.
