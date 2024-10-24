# java-racingcar-precourse

### 구현할 기능 목록
- [ ] 사용자에게 입력을 받는다.
  - [ ] 각 자동차의 이름을 입력 받는다.
    -  [ ] 자동차 이름을 쉼표(,)를 기준으로 구분한다.
  - [ ] 몇번의 이동(시도할 횟수)을 할 것인지 입력받는다.
  - [ ] 예외 처리
    - [ ] 입력된 자동차의 이름이 5자를 넘으면 `IllegalArgumentException`을 발생시킨다.
    - [ ] 시도할 횟수가 양수가 아니면 `IllegalArgumentException`을 발생시킨다.

- [ ] 경기에 대한 시뮬레이션을 구현한다.
  - [ ] 자동차를 조건에 따라 전진시킨다.
    -  [ ] 무작위 값(0~9)을 구한 후 4 이상이면 전진한다.
    -  [ ] 모든 자동차에 대해 진행한다.
    
  - [ ] 경기 진행을 출력한다.
    - [ ] 각 자동차의 이름을 포함하여 전진한 상태를 출력한다.
    - [ ] 입력 받은 (시도할 횟수)만큼 진행하면 우승자를 출력하고 종료한다.


### 학습할 목록
- [ ] 테스트 코드 API 학습: 
- [ ] 디버깅 학습 (feat/IntelliJ): 