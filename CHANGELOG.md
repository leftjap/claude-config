## 2026-03-30

### Changed
- 전 프로젝트 CLAUDE.md에서 playbook→opus 명칭 전면 교체 — opus 레포 리네임 반영. (CLAUDE.md ×7, common-rules.md)
- opus CLAUDE.md에서 Opus 관리 사항 4건 삭제 (모호한 표현 금지, opus.md 참조 포인터, 200줄 제한, 변경 이력 3일분) — HumanLayer 연구 기반 CLAUDE.md 최적화
- keep CLAUDE.md에서 switchTab() else 블록 항목 삭제 — 조건부 판단 규칙은 작업지시서 Step이 확실
- gym CLAUDE.md에서 syncFromServer 타임스탬프 항목 삭제 — 특정 함수 비교 연산자 규칙은 작업지시서 Step이 확실
- study CLAUDE.md에서 saveLangData()+saveToServer() 호출 및 언어 전환 패턴 항목 삭제 — 로직 순서·코딩 패턴은 작업지시서 Step이 확실
- clasp push 규칙을 opus CLAUDE.md(공통)로 통합하고 keep·gym·study·docs 개별 항목 삭제 — 4곳 중복 제거, HumanLayer 연구 기반 지시 수 최소화

### Removed
- opus CLAUDE.md: decisions/ 디렉토리 참조 (실사용 없음)
