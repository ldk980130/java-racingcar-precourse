## 기능 구현 목록
- 입력
    - 자동차 이름 입력 받기
    - 시도할 횟수 입력 받기
    - 예외 발생 시 에러 메시지 출력 후 다시 입력 받기
- 입력 검증
    - 자동차 이름이 5자를 초과하면 예외 발생
    - 자동차 이름이 아무것도 입력되지 않으면 예외 발생
    - 시도 횟수가 1이상의 정수가 아니면 예외 발생
- 핵심 레이스 로직
    - 입력받은 이름을 통해 n개의 Car 객체 생성 및 등록
    - 난수 결과로 자동차가 전진 또는 멈추는 레이스 기능 구현
    - 시도 횟수가 모두 끝나면 최종 우승자 자동차 구하는 기능 구현
- 출력
    - 한 시도마다 레이스 진행상황을 출력
    - 모든 시도가 끝나면 최종 우승자 이름을 출력