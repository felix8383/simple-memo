# simple-memo

실행: https://felix8383.github.io/simple-memo/ 에 접속하여 이메일·비밀번호로 가입/로그인합니다. 메모 입력 → 저장 → 삭제. 서버 빌드 없이 index.html 하나를 GitHub Pages(main / root)로 제공합니다.

검증: memos 4개 열과 본인 조회·추가·삭제 RLS 적용, Supabase 보안 검사 지적 0건. 브라우저 기능 검증 결과는 후속 기록 예정.

미해결: 기존 test 프로젝트의 Confirm email이 켜져 있습니다. 자동 로그인 실습에는 이 설정을 꺼야 하나, 대시보드 로그인 중 별도 인증 사이트 접근이 자동 승인 검토에서 차단되어 변경하지 않았습니다.
