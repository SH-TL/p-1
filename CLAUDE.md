# 작업지침
- 한국어 사용
- /caveman 스킬 사용
- 일반적인 작업 흐름 : /grill-with-docs, /to-prd, /to-issues, /tdd and /diagnose, /improve-codebase-architecture(이 스킬은 필요할 때만 사용)
- 최대한 mattpocock 스킬들을 활용

## Agent skills

### Issue tracker

이슈는 `.scratch/<feature-slug>/` 아래 로컬 마크다운 파일로 관리합니다. `docs/agents/issue-tracker.md` 참조.

### Triage labels

기본 레이블 문자열 사용 (`needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`). `docs/agents/triage-labels.md` 참조.

### Domain docs

단일 컨텍스트 레이아웃 — 루트의 `CONTEXT.md` + `docs/adr/`. `docs/agents/domain.md` 참조.
