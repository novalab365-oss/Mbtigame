# MBTI 게임 플랫폼 P1 — 중간 작업본

공통 로비 1개 + 독립 게임 16개. 현재 ENTJ만 개발 중이며 나머지 15개는 잠금 상태입니다.

최상위 index.html부터 실행하세요. ZIP을 풀고 전체 폴더 구조를 유지한 채 정적 서버로 실행하세요. index.html 단독 교체는 불가합니다. Netlify Drop: https://app.netlify.com/drop

설계 기준: docs/PROJECT_CONTRACT_KO.md
재개 지점: docs/TASK_STATE.json
전체 플레이와 실제 iPad 검수는 미완료. GitHub/기존 배포본 미반영.

검사: python3 tools/check_structure.py / python3 games/entj/tools/check_resources.py
브라우저 검사: node tools/check_platform.cjs (Playwright 및 외부 QA 런타임 필요, 제품 ZIP에 브라우저·테스트 폰트 미포함)
