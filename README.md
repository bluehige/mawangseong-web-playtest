# 마왕성 v1.2.2 피드백 수정 후보 · PC Web

현재 사용자 QA용 최신 빌드 하나만 보관하는 데스크톱 브라우저 테스트 저장소입니다.

- 플레이: https://bluehige.github.io/mawangseong-web-playtest/
- 테스트 채널: `v122-feedback-routing-performance-web-qa`
- 기준 소스 저장소: `bluehige/mawangseong-demo`
- 기준 소스 브랜치: `codex/v122-ui-simplification`
- 기준 소스 커밋: `5b423c9ef734c310cd5c9c688f9e6d4cf9ffd146`
- 소스 검토 PR: https://github.com/bluehige/mawangseong-demo/pull/80
- 빌드 엔진: Godot 4.5.2
- PC Web PCK: 242,581,944바이트
- PCK SHA-256: `85c3db1a1fcd47f04ee79e5a46ed0e064ea732bdccfdaccdf4567b09f2c76765`

포함 변경:

- DAY 1~5 관리·전투 UI 개편과 DAY 1 곱 전열·후열 선택
- 샛길을 모든 수비 몬스터가 사용하도록 경로 규칙 통일
- 샛길 중간 진입 시 연결 경로 재탐색 보강
- 금고 침입자에게 수비 몬스터가 접근해 공격하도록 보강
- 왕좌 공격 모션 표시
- 전투 중 동적 오버레이 전면 재그리기를 부분 갱신으로 전환해 프레임 드롭 완화

1920×1080 Full-canvas와 1366×768/1280×720 Compact 브라우저 검수를 통과한 사용자 테스트 후보입니다. 정식 출시 태그나 Steam 배포본을 대체하지 않으며 모바일 Web 및 Windows QA 빌드는 이 저장소에 포함하지 않습니다.
