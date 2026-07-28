# 마왕성 v1.2.2 후보 S08 · PC Web

UI 단순화와 배치·복도 이동 수정본을 확인하는 데스크톱 브라우저용 공개 테스트 빌드입니다.

- 플레이: https://bluehige.github.io/mawangseong-web-playtest/
- 테스트 채널: `v122-ui-s08-deployment-polish-playtest`
- 기준 소스 브랜치: `bluehige/mawangseong-demo`의 `codex/v122-ui-simplification`
- 기준 소스 커밋: `321d56afe264488bb85593d2d1954b092d80532e` + S00~S08 승인 작업 트리
- 빌드 엔진: Godot 4.5.2
- 포함 변경: 관리·전투 UI 단순화, 전장 직접 명령, 성 구조 편집 버튼 제거, 복도 장거리 순찰, 배치 화면의 이전 전투 액터 숨김
- PC Web PCK: 242,757,700바이트
- PCK SHA-256: `4317d76bd02beec77f651c05eaa1114b2a964a5a7369e008f2ad1bc78d2c3b90`

사용자 최종 검수 전 후보이며 정식 출시 태그나 Steam 배포본을 대체하지 않습니다. 모바일 Web 프리셋은 포함하지 않습니다.

## v2.0 Phase 11 블라인드 플레이테스트

- 플레이: https://bluehige.github.io/mawangseong-web-playtest/v20-p11/
- 테스트 채널: `v20-p11-blind-playtest`
- 기준 소스: `bluehige/mawangseong-demo@4b687aeea80b487f237e6c153dce8600989ec81b`
- 빌드 엔진: Godot 4.5.2
- PC Web PCK: 231,748,912바이트
- PCK SHA-256: `cc0cc314d59bf2dec3e95e066dbf5d74016baaa38827dce4fbe984315920c7fa`

기존 루트 주소의 v1.2.1 공개판은 그대로 유지하며, 위 하위 주소만 v2.0 Phase 11 외부 테스트에 사용합니다.

## v2.0 Phase 11R 비주얼 커맨드 보드 플레이테스트

- 플레이: https://bluehige.github.io/mawangseong-web-playtest/v20-p11r/
- 테스트 채널: `v20-p11r-visual-command-board-playtest`
- 검수 기능 소스: `bluehige/mawangseong-demo@1abb2b63b03d3711bc014b9d3b081e9300f7041d`
- release/v2.0 병합: `bluehige/mawangseong-demo@5d1d8fc603392e26a7e3d5fc1f862aa8bc0faf59`
- 빌드 엔진: Godot 4.5.2
- PC Web PCK: 231,596,228바이트
- PCK SHA-256: `6454fa55b35e14aba9ef87cd1daee1bd0eed780acb759328a7bf5dca1ee73f60`

이 주소는 준비·전투·결과 UI/UX 재설계 검증용입니다. 기존 루트 v1.2.1과 `/v20-p11/` 빌드는 교체하지 않습니다.

## v2.0 Phase 11S 고정 침입로 전략 배치 플레이테스트

- 플레이: https://bluehige.github.io/mawangseong-web-playtest/v20-p11s/
- 테스트 채널: `v20-p11s-fixed-castle-route-strategy-playtest`
- 검수 기능 소스: `bluehige/mawangseong-demo@afa2cc592cffc1c758520f3d9d4c1f8472ab97e0`
- release/v2.0 병합: `bluehige/mawangseong-demo@8b5022fa84a2a4697d02168972798f4ed26eac4f`
- 빌드 엔진: Godot 4.5.2
- PC Web PCK: 231,614,192바이트
- PCK SHA-256: `9d3a381dab5db66374f607bf920958117186d8a04359b5b1685aaf23132e3284`

이 주소는 하나의 고정 침입로와 네 전략 구역에서 시설·몬스터 배치 조합을 검증하는 전용 공개본입니다. 기존 루트 v1.2.1과 `/v20-p11/`, `/v20-p11r/` 빌드는 교체하지 않습니다.

## v2.0 Phase 11T 순차 방어·몬스터 배치 플레이테스트

- 플레이: https://bluehige.github.io/mawangseong-web-playtest/v20-p11t/
- 테스트 채널: `v20-p11t-defense-stages-clarity-playtest`
- 검수 기능 소스: `bluehige/mawangseong-demo@d1829eb21951ba8d1b4aebdf3103c148c4524c9e`
- release/v2.0 병합: `bluehige/mawangseong-demo@4a15d3559f73e5dc5e6e636be82584d69b7d7a40`
- 빌드 엔진: Godot 4.5.2
- PC Web PCK: 231,636,336바이트
- PCK SHA-256: `35572910695d3e957bc3c394ab25a9ef1f950d019d394bbad53befd0cb14366c`

이 주소는 성문 전초부터 왕좌까지 각 구역을 순서대로 방어하는 흐름, 초상화 몬스터의 직접 드래그 배치, 밝아진 전투 지도와 방별 명령을 함께 검증하는 전용 공개본입니다. 기존 루트와 `/v20-p11/`, `/v20-p11r/`, `/v20-p11s/` 빌드는 교체하지 않습니다.
