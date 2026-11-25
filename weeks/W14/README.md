# W14 · MCP ①: 기능을 AI에 꽂는 표준 콘센트

> 5단계 · 혼자 일하기 (MCP·에이전트)

## 이번 주 핵심 3가지
- MCP = 연결 규격(기능 아님): RAG·예측 모델·팹 데이터를 같은 방식으로 꽂음
- 구조: Host·Client·Server / Tools·Resources·Prompts
- 도구 설명문과 읽기 vs 쓰기 권한

## 실습
FAB-1 조회 도구 + W07 predict_thickness() + W13 search_sop()를 MCP 도구로 연결해 자연어로 호출 (실습 키트 템플릿)

## 💡 LLM에게 이렇게 물어보기
"3번 챔버 두께 예측하고 SOP에서 조치 방법 찾아줘"

## 🤖 AI 코딩 역량
도구 설명문(description) 잘 쓰기 MCP Inspector로 메시지 관찰

## 🆓 무료 도구
FastMCP / MCP Python SDK (오픈소스) / Claude Desktop 무료* / 대안: 파이썬 클라이언트+Groq

## 강의 자료
<!-- 수업 전에 이 폴더에 슬라이드·노트북·데이터 링크를 올리세요 -->
- (슬라이드) `slides.pdf`
- (실습 노트북) `lab.ipynb`

## 과제 제출물 — 내 과제 저장소의 `W14/` 폴더에
- [ ] `mcp_server/*.py` — MCP 서버 코드 (mcp_server 폴더 안)
- [ ] `screenshot.png|screenshot.jpg` — Claude(또는 대체 클라이언트)에서 도구가 호출된 화면 캡처
- [ ] `explain.md` — 핵심 코드 5줄을 골라 각 줄에 내 말로 단 설명
- [ ] `prompts.md` — 사용한 프롬프트와 검증 방법 (어떤 데이터로 확인했는지)

마감: [일정표](../../schedule.csv)의 `due` 시각 (한국 시간). 마감 시각까지 GitHub에 **push된 커밋**만 채점합니다.

## 선택 심화 (자료만 제공)
프로토콜 세부·원격 서버·OAuth
