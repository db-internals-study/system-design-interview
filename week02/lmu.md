# 2장 개략적인 규모

## 2의 제곱수
## 모든 프로그래머가 알아야하는 응답지연 값
- L1 캐시 참조: 0.5 ns
- 분기 예측 오류: 5 ns
- L2 캐치 참조: 7 ns
- mutex lock/unlock: 100ns
- main memory 참조: 100 ns
- zippy로 1KB 압축: 10,000 ns
- 1 Gbps 로 2KB 패킷 전송: 20,000 ns
- 메모리에서 1MB 순차적으로 read: 250,000 ns
- 같은 데이터 센터 내에서의 메시지 왕복 지연시간: 500,000 ns
- 디스크 탐색: 10ms
- 네트워크에서 1MB 순차적으로 read: 10ms
- 디스크에서 1MB 순차적으로 read: 30ms

## 가용성에 관계된 수치들
- https://uptime.is/

## 효과적 면접을 위한 4단계 접근법
- 1단계 문제 이해 및 설계 범위 확정
- 2단계 개략적인 설계안 제시 및 동의 구하기
- 3단계 상세 설계
- 4단계 마무리

## 해야할 것
- 질문을 통해 확인하라. 스스로 내린 가정이 옳다 믿고 진행하지 마라
- 문제의 요구사항을 이해하라
- 정답이나 최선의 답안 같은 것은 없다는 점을 명심하라
- 면접관이 여러분의 사고 흐름을 이해할 수 있도록 하라
- 가능하다면 여러 해법을 함께 제시하라
- 개략적 설계에 면접관이 동의하면, 각 컴포넌트의 세부사항을 설명하기 시작하라. 가장 중요한 컴포넌트부터 진행하라
- 면접관의 아이디어를 이끌어 내라
- 포기하지 마라

## 하지 말아야할 것
- 전형적인 면접 문제들에도 대비하지 않은 상태에서 면접장에 가지 마라
- 요구사항이나 가정들을 분명히 하지 않고 설계를 제시하지 마라
- 특정 컴포넌트의 세부사항을 너무 처음부터 깊이 설명하지 마라
- 진행 중에 막혔다면, 힌트를 청하기를 주저하지 마라
- 소통을 주저하지 마라
- 면접관이 끝났다고 말하기 전까지 끝난 것이 아니다.
