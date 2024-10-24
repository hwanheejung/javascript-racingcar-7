# javascript-racingcar-precourse

## 🍴 About

- 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
- 각 자동차에 이름을 부여할 수 있다. 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.
- 자동차 이름은 쉼표(,)를 기준으로 구분하며 이름은 5자 이하만 가능하다.
- 사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
- 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.
- 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다.
- 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분한다.
- 사용자가 잘못된 값을 입력할 경우 "[ERROR]"로 시작하는 메시지와 함께 Error를 발생시킨 후 애플리케이션은 종료되어야 한다.

<br />

## 🏁 Feature Checklist

### 입력

- [x] 경주할 자동차 이름 쉼표(,)를 기준으로 입력

  - [x] 각 자동차 이름이 5자 이하인지 확인
  - [x] 빈 문자열인지 확인

- [x] 이동할 횟수 확인
  - [x] 입력된 값이 숫자인지 확인
  - [x] max number 설정
  - [x] 음수

### 기능

- [x] 0에서 9 사이의 랜덤 번호 생성
- [x] 랜덤값이 4 이상인지 확인

### 출력

- [x] 차수별 실행 결과
- [x] 우승자 출력 (쉼표로 구분)

<br />

## ⌨ Programming Requirements

- indent(인덴트, 들여쓰기) depth를 3이 넘지 않도록 구현한다. 2까지만 허용한다.
- 3항 연산자를 쓰지 않는다.
- 함수(또는 메서드)가 한 가지 일만 하도록 한다.
- Jest를 이용하여 정리한 기능 목록이 정상적으로 작동하는지 테스트 코드로 확인한다.
- JavaScript Code Conventions을 준수한다.

<br />

## 🤔 Focus

- 테스트코드
- 폴더 구조
