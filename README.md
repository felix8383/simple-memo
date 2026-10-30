# simple-memo

실행: https://felix8383.github.io/simple-memo/ 에 접속하여 이메일·비밀번호로 가입/로그인합니다. 메모 입력 → 저장 → 삭제. index.html 하나를 GitHub Pages(main / root)로 제공합니다.

검증: 실제 배포 첫 화면 접속 및 로그인 UI 정상. memos 4개 열, RLS 본인 조회·추가·삭제 적용, 익명 조회와 UPDATE 권한 없음. 트랜잭션 내 두 사용자로 타인 조회·삭제·소유자 위조 추가 차단 검증(테스트 데이터 모두 롤백). Supabase 보안 검사 지적 0건.

미해결: test 프로젝트의 Confirm email이 켜져 있습니다. 가입 직후 자동 로그인에는 이 설정을 꺼야 하나, 대시보드 로그인 중 auth.openai.com 접근이 자동 승인 검토에서 차단되어 변경하지 않았습니다. 회원가입·자동 로그인·메모 저장/유지/삭제·재로그인 브라우저 검증은 미완료입니다.
