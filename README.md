# 자동차 경주 게임
- [ ] 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
- [ ] 각 자동차에 이름을 부여할 수 있다. 자동차 이름은 5자를 초과할 수 없다.
- [ ] 자동차 이름은 쉼표(,)를 기준으로 구분한다.
- [ ] 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.
- [ ] 사용자는 몇 대의 자동차로 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
- [ ] 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.
- [ ] 자동차의 상태를 화면에 출력한다. 어느 시점에 출력할 것인지에 대한 제약은 없다.
- [ ] 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다.

## 프로그램 요구사항
- [ ] 경주에 참가하는 자동차들의 이름을 입력한다.
- [ ] 게임 시도 횟수를 입력한다.
- [ ] 시도 횟수만큼 자동차 경주가 진행된다.
  - [ ] 한 번 경기를 할 때마다 실행 결과를 출력한다.
- [ ] 최종 우승자를 출력한다.

### Name
- [x] 5자를 초과할 수 없다.
- [x] null, 공백, 빈 문자열은 이름이 될 수 없다.

### Position
- [x] 0보다 작을 수 없다.
- [x] 값 증가

### RandomNumberGenerator
- [x] 0~9 사이의 난수를 반환한다. 
