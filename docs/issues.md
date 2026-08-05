# 프로젝트 문제 보고서 (Issue Tracker)

웹사이트 구축 및 운영 과정에서 발생하는 문제점 및 해결 과정을 기록하는 문서입니다.

## [해결됨] 1. Contact 블록 렌더링 오류
- **문제 발생일:** 2026-08-04
- **증상:** `_index.md`에서 `contact` 블록을 사용했을 때 `partial "hbx/blocks/contact/block.html" not found` 오류와 함께 빌드 실패
- **원인:** Hugo Blox 최신 버전(v5/kit)에서 기본 contact 블록의 경로 또는 지원 방식이 변경됨
- **해결 방안:** `contact` 전용 블록 대신 일반 `markdown` 블록을 활용하여 이메일 및 카카오톡 채널 안내 텍스트를 직접 구성하는 방식으로 대체하여 해결 완료

## [해결됨] 2. GitHub Push 인증 실패
- **문제 발생일:** 2026-08-05
- **증상:** `git push -u origin main` 실행 시 `Invalid username or token` 오류 발생
- **원인:** 백그라운드 터미널 환경에서 GitHub 비밀번호(또는 Token) 인증 창을 띄우거나 처리할 수 없었음
- **해결 방안:** 사용자가 직접 로컬 터미널에서 `gh auth login`을 수행하거나 SSH를 사용하여 푸시하도록 안내하여 해결 위임

---
*참고: 본 보고서는 AI 어시스턴트에 의해 작업이 진행될 때마다 지속적으로 업데이트됩니다.*
