---
project: revisiting_alfred
purpose: ALFRED 검증 데이터의 크라우드소싱 명령어 오류를 분류·정제한 명령어 세트를 공개하고 GenPlan 2025 워크숍 논문 결과를 보관한다
status: 종료
stage: 논문이 AAAI 2025 GenPlan 워크숍에 채택됐고 정제 명령어 세트와 포스터를 공개한 뒤 추가 작업 없이 사용자 결정으로 종료했다 (기준일 2025-03-04, 종료 지정 2026-09-25)
updated: 2026-09-25
next: []
decisions: []
blockers: []
resources: []
related:
  - HiAlfred
  - alfred_refined
docs:
  - README.md
  - refined_valid_seen_commands.json
  - refined_valid_unseen_commands.json
---

# Revisiting ALFRED 현황

> 기재 정책: zebehn/mastermind docs/STATUS_POLICY.md (v1.0). 최종 갱신 2026-09-25 (KST).

## 요약

ALFRED 벤치마크 검증 데이터의 명령어를 정제한 결과를 공개하는 저장소다. 논문 "Revisiting ALFRED: Refining commands for evaluating language-guided task planning"이 AAAI 2025 GenPlan 워크숍에 채택됐다. 2026-09-25 사용자 결정으로 종료했다.

## 현재 단계

- 정제 명령어 세트 두 종을 공개했다: valid_seen 251건, valid_unseen 255건(JSON 항목 수, 열람용 마크다운 포함).
- 워크숍 포스터를 추가했다(2025-03-04).
- 2025-03-04 이후 변경은 없다.
- README의 valid_unseen JSON 링크가 valid_seen 파일을 가리킨다. 고치지 않은 상태다.

## 최근 진행

- 2026-09-25 사용자 결정으로 종료 지정, STATUS.md 신설
- 2025-03-04 GenPlan 2025 포스터 추가, README 갱신
- 2025-01-31 정제 명령어 세트(valid_seen, valid_unseen) 공개

## 다음 할 일

- 없음

## 결정 대기

- 없음

## 차단 요인

- 없음

## 핵심 문서

- [README.md](README.md): 논문 초록, 포스터, 파일 목록
- [refined_valid_seen_commands.json](refined_valid_seen_commands.json): valid_seen 정제 명령어
- [refined_valid_unseen_commands.json](refined_valid_unseen_commands.json): valid_unseen 정제 명령어

## 관련 저장소

- HiAlfred: ALFRED 기반 사람 상호작용 벤치마크(같은 ALFRED 계열 후속 작업)
- alfred_refined: ALFRED 데이터에서 절차 기반 명령어를 생성하는 코드(카탈로그 기준 관련 저장소)
