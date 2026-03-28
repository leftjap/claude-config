# backlog-archive.md — 완료 백로그 아카이브

> playbook.md에서 완료 확인된 백로그를 이관한 문서. 원본은 git log에 보존.

---

## 2026-03 완료

| ID | 프로젝트 | 작업 | 완료일 | 요약 |
|---|---|---|---|---|
| B-31 | 오늘의내비 | 피드백 지침서 분리 (AGENTS.md 35KB→5KB + 소연/피드백지침서.md 신규) | 3/28 | 완료 |
| B-22 | keep | 파트너 글에 달린 댓글이 표시되지 않는 버그 | 3/27 | ui.js 댓글 함수 3곳에서 localStorage 키에 _LS_PREFIX 누락 |
| B-23 | keep | 해외 결제 내역 알림이 가계부에 반영되지 않음 | 3/27 | 날짜 정규식 검증, cleanMerchantName 통합, mergeServerAll 경쟁 조건 수정, CLAUDE.AISUBSCRIPTION→Anthropic 매핑, 통화코드 접두어 제거 패턴 |
| B-24 | keep | 휴대폰 요금 등 '승인' 외 형식 알림이 가계부에 반영되지 않음 | 3/27 | parseSMSServer/parseSMS에 자동결제 분기 추가. 아이폰 단축어 "자동결제" 트리거 추가 |
| B-28 | 운동 | 종목 선택 UI + 운동 중 추가/삭제 + 헤더 개편 | 3/27 | Phase 1-A~3-A 완료. 삭제 함수 syncToServer 수정 포함 |
| B-29 | keep | 새로고침 시 마지막 문서 즉시 복원 | 3/27 | curIds/activeTab을 LocalStorage에 저장. 서버 동기화 완료 후 에디터도 갱신 |
| B-34 | keep | 가계부 날짜 수정 date picker 버그 — iOS Safari/PWA showPicker() 미작동 | 3/27 | picker 호출 전 요소 임시 가시화 |
| B-35 | keep | 파트너 모드 LocalStorage 오염 방지 | 3/27 | enterPartnerMode()에서 LocalStorage 쓰기 제거, data.js에 파트너 모드 분기, 동기화 차단 |
| B-36 | keep | GAS 다세대 백업 + 무결성 검증 | 3/27 | 1일1회 7일분 날짜별 백업, expenses 급변 차단, 수동 복원 유틸 |
| B-37 | keep | saveDatabase 카드 교차 오염 검증 | 3/27 | OWNER_CARDS 매핑으로 타 사용자 카드 감지 시 저장 차단 |
| B-45 | playbook | CLAUDE.md 생성 + 세션 종료 규칙 보강 + 작업환경 섹션 | 3/28 | 완료 |
| B-13 | 운동 | 유산소 중 세션 소실 | 완료 3/28 | visibilitychange/beforeunload 저장 + 30초 자동저장 + 복원 시 운동 화면 전환 |
| B-14 | 운동 | 새로고침 시 세션 복원 실패 | 완료 3/28 | B-13과 함께 진행 |
| B-46 | 오늘의내비 | AGENTS.md 경량화 — 소연 피드백 지침서 분리 | 완료 3/28 | B-31과 통합 완료 |
