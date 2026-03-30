# CHANGELOG.md 도입

## 날짜
2026-03-31

## 상태
채택

## 맥락
기능 추가·버그 수정 작업 내역을 역추적할 기록이 없었다. Git 커밋 로그는 너무 세밀하고, decisions/는 큰 결정만 담고, backlog.md는 할 일 관리 용도라 완료된 작업의 맥락을 남기기에 부적합했다.

## 결정
프로젝트별 CHANGELOG.md를 도입한다. Keep a Changelog 컨벤션 기반으로 Added/Changed/Fixed/Removed를 날짜별로 기록한다. 모든 작업지시서의 커밋 Step 직전에 CHANGELOG.md 갱신 Step을 포함한다.

## 근거
- Keep a Changelog (keepachangelog.com): 업계 표준 컨벤션
- gatlin.io "Changelogs, Captain's Logs, and ADRs": Changelog는 사용자(미래의 자신)용, ADR은 결정 근거용으로 역할 분리
- 현재 운영 체계에서 Git 커밋(너무 세밀)과 decisions/(큰 결정만) 사이의 중간 계층이 부재

## 결과
- 작업지시서마다 CHANGELOG.md 갱신 1줄 추가 (유지 부담 최소)
- 문제 발생 시 날짜로 역추적 가능
- common-rules.md에 갱신 규칙 추가
