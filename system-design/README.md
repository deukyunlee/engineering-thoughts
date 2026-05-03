# System Design

대규모 시스템을 설계할 때 마주치는 문제들과 해결 패턴을 정리합니다.

단순한 요약이 아니라, 트레이드오프나 대안 설계, 실무에서 떠오른 의문들을 **나의 생각** 섹션에 함께 정리하는 것을 목표로 합니다.

## 1. 기초

| 문서 | 내용 |
|------|------|
| [사용자 수에 따른 규모 확장성](./user-based-scalability/user-based-scalability.md) | 사용자, 트래픽 규모가 커질 때 아키텍처 변경 대응 |
| [개략적인 규모 추정](./scale-estimation/scale-estimation.md) | QPS, 저장, 대역폭 등을 계략적으로 측정 |
| [시스템 설계 면접 공략](./system-design-interview/system-design-interview.md) | 면접에서 요구되는 사고 과정과 전개 순서 |

## 2. 케이스 스터디

| 문서 | 내용 |
|------|------|
| [안정 해시 설계](./consistent-hash/consistent-hash.md) | 노드 증설 및 장애 시 리밸런싱을 줄이는 전략 |
| [분산 시스템에서의 유일 ID](./unique-id/unique-id.md) | 유일한 식별자 생성 전략 |
| [URL 단축기](./url-shortener/url-shortener.md) | URL 단축기 설계 |
| [처리율 제한 장치](./rate-limiter/rate-limiter.md) | API, 서비스별 요청 상한과 알고리즘 선택 |
