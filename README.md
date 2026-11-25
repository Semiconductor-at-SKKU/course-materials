# AI Assistant Engineering — 2027년 1학기

반도체 전공 AI 초보자를 위한 16주 과정입니다. 전 과정을 **가상 팹 데이터셋 FAB-1** 하나로 진행하며, 매주 결과물이 다음 주 재료가 됩니다.

- 강의 자료: 이 저장소의 `weeks/` 폴더 (주차별 README)
- 과제 제출: 본인 전용 비공개 저장소 → [제출 방법](SUBMISSION.md)
- 마감 일정: [schedule.csv](schedule.csv)
- 보안 규칙: [SECURITY_RULES.md](SECURITY_RULES.md)

## 주차별 안내

| 주차 | 주제 | 실습 |
| --- | --- | --- |
| [W01](weeks/W01/README.md) | AI란 무엇인가? '신입 AI 키우기' 지도 | LLM과 첫 대화 + FAB-1 웨이퍼 맵 이미지 설명 받기 |
| [W02](weeks/W02/README.md) | 파이썬 ① 변수·조건문 + 프롬프트 작성법 | FAB-1 챔버 압력이 10 torr 이상이면 경고를 출력하는 코드 |
| [W03](weeks/W03/README.md) | 파이썬 ② 반복문·함수·리스트·딕셔너리 | FAB-1 한 LOT(웨이퍼 25장) 측정값에서 불량 웨이퍼 골라내는 함수 |
| [W04](weeks/W04/README.md) | Pandas로 공정 데이터 다루기 | FAB-1 데이터(결측치 포함)로 LOT별 수율 계산 |
| [W05](weeks/W05/README.md) | 그래프로 데이터 보기 (EDA) | FAB-1 온도·압력과 불량의 관계 그래프 → 의심 인자 3개 적어 두기 |
| [W06](weeks/W06/README.md) | 머신러닝 ① 분류: 불량인가 정상인가? | FAB-1 센서로 Pass/Fail 예측 + 불량 원인 인자 순위 (W05 의심 인자와 비교) |
| [W07](weeks/W07/README.md) | 머신러닝 ② 회귀: 가상 센서로 두께 예측 | FAB-1 센서로 박막 두께 예측 + predict_thickness() 함수 저장 |
| [W08](weeks/W08/README.md) | 📌 사전 발표 | 5분 발표 + 피드백 |
| [W09](weeks/W09/README.md) | 딥러닝과 LLM: AI는 어떻게 똑똑해졌나? | FAB-1 질문 하나로 두 답변 비교 평가 (RLHF 체험) |
| [W10](weeks/W10/README.md) | 프롬프트 엔지니어링: 작성에서 설계·비교로 | W06~07 FAB-1 예측 결과로 교대조 경고 리포트 작성 (채팅창에서) |
| [W11](weeks/W11/README.md) | LLM API: 파이썬에서 LLM 부르기 | FAB-1 예측값을 넣으면 리포트를 써주는 스크립트 (템플릿 제공) |
| [W12](weeks/W12/README.md) | RAG ① 지식 베이스 만들기 | FAB-1 SOP 20개 + 과거 8D 보고서 10개로 지식 베이스 구축 (템플릿 제공) |
| [W13](weeks/W13/README.md) | RAG ② 찾아보고 답하기 + 검색 함수로 묶기 | FAB-1 SOP 챗봇 완성 → 틀린 답 원인 찾아 개선 → search_sop() 함수로 정리 |
| [W14](weeks/W14/README.md) | MCP ①: 기능을 AI에 꽂는 표준 콘센트 | FAB-1 조회 도구 + W07 predict_thickness() + W13 search_sop()를 MCP 도구로 연결해 자연어로 호출 (실습 키트 템플릿) |
| [W15](weeks/W15/README.md) | MCP ② 통합 에이전트 + 하네스: 나만의 AI Assistant 완성 | W08에서 고른 FAB-1 불량의 숨은 원인을 에이전트로 찾기 → SOP·8D 인용 + 안전 규칙 3개 |
| [W16](weeks/W16/README.md) | 📌 기말 발표 & AGI 토론 | 10분 발표 ('FAB-1 OO 불량의 원인과 조치') + Notebook·리포트·PRD 제출 |
