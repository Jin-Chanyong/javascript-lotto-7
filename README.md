# javascript-racingcar-precourse

## 기능 요구 사항

- 로또 번호의 숫자 범위는 1~45까지이다.
- 1개의 로또를 발행할 때 중복되지 않는 6개의 숫자를 뽑는다.
- 당첨 번호 추첨 시 중복되지 않는 숫자 6개와 보너스 번호 1개를 뽑는다.
- 당첨은 1등부터 5등까지 있다. 당첨 기준과 금액은 아래와 같다.
- 1등: 6개 번호 일치 / 2,000,000,000원
- 2등: 5개 번호 + 보너스 번호 일치 / 30,000,000원
- 3등: 5개 번호 일치 / 1,500,000원
- 4등: 4개 번호 일치 / 50,000원
- 5등: 3개 번호 일치 / 5,000원
- 로또 구입 금액을 입력하면 구입 금액에 해당하는 만큼 로또를 발행해야 한다.
- 로또 1장의 가격은 1,000원이다.
- 당첨 번호와 보너스 번호를 입력받는다.
- 사용자가 구매한 로또 번호와 당첨 번호를 비교하여 당첨 내역 및 수익률을 출력하고 로또 게임을 종료한다.
- 사용자가 잘못된 값을 입력할 경우 "[ERROR]"로 시작하는 메시지와 함께 Error를 발생시키고 해당 메시지를 출력한 다음 해당 지점부터 다시 입력을 받는다.

## 기능 목록 단위

- [ ] 1. 로또 구매 로직 구현

  - [ ] 1-1. 사용자로부터 로또 구입 금액 입력받기
    - [ ] 입력된 금액이 1000원 단위로 나누어 떨어지지 않거나, 잘못된 입력 시 다시 입력.
  - [ ] 1-2. 구입 금액에 따라 구매할 로또 수량을 계산하기
  - [ ] 1-3. 구매한 로또 수량 만큼 로또 번호 생성하고 출력하기
    - [ ] 로또 번호는 오름차순으로 정렬.

- [ ] 2. 당첨 번호 및 보너스 번호 입력 로직 구현

  - [ ] 2-1. 사용자로부터 당첨 번호 6개와 보너스 번호 1개를 입력받기
    - [ ] 입력된 번호가 1부터 45사이의 정수가 아니거나, 중복이 있거나, 쉼표로 구분되지 않을 시 다시 입력.

- [ ] 3. 당첨 내역 비교 및 결과 계산

  - [ ] 3-1. 구매한 로또 번호와 당첨 번호를 비교하여 당첨 등수 계산하기
  - [ ] 3-2. 1등부터 5등까지의 당첨 횟수 출력하기

- [ ] 4. 수익률 계산 및 출력

  - [ ] 4-1. 전체 당첨 금액 계산하기.
  - [ ] 4-2. 수익률을 계산해 소수점 둘째 자리에서 반올림하여 출력하기.

- [ ] 5. 테스트 코드 작성

  - [ ] Jest 를 이용하여, 위 1, 2, 3, 4 가 제대로 기능하는지, 출력값은 정확한지를 테스트한다.
