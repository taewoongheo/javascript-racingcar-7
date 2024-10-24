# javascript-racingcar-precourse

## 미션 간단 설명

자동차 경주게임을 구현하는 미션입니다. n 대의 자동차와 전진횟수를 입력받고, 랜덤으로 전진하여 우승한 자동차를 출력하는 프로그램입니다.

## 요구사항 및 제약조건 정리

### 입력 제약조건

- `@woowacourse/mission-utils` 에서 제공하는 `Console.readLineAsync()` 활용하기
- 잘못된 값 입력 시 "\[ERROR]" 로 시작하는 메시지와 함께 `Error` 를 발생시킨 후 종료
- 잘못된 입력
  - \[자동차] 이름이 빈 문자열일 경우
  - \[자동차] 자동차 이름이 5자 초과일 경우

### 출력 제약조건

- `@woowacourse/mission-utils` 에서 제공하는 `Console.print()` 활용하기
- 우승자가 여러명일 경우 `,` 로 구분하기

### 기능 요구사항

- `,` 을 기준으로 자동차를 입력받기
- 전진횟수 `n` 입력받기
- `@woowacourse/mission-utils` 의 `Random.pickNumberInRange()` 를 이용하여, 각 자동차마다 전진을 위한 랜덤 값 생성
- 우승자 출력. 여러 명인 경우 `,` 로 구분해 출력하기

## 구현할 기능 목록

- 입력모듈
  - 문자열 입력 파싱함수
    - 제약조건)
      - `@woowacourse/mission-utils` 에서 제공하는 `Console.readLineAsync()` 활용하기
      - `,` 으로 자동차 이름 구분
- 자동차 클래스
  - 자동차 이름 유효성 검사 함수
    - 제약조건)
      - 이름이 비어있으면 안됨
      - 각 이름은 5자를 초과할 수 없음
  - 전진가능여부 확인하는 메서드
  - 전진횟수 증가하는 메서드
- 경주 클래스
  - 경주 초기화 메서드
  - 경주 시작 메서드
  - 각 자동차 별 전진횟수 업데이트
  - 차수별 실행결과 출력 메서드
  - 우승자 판별 메서드
  - 결과 출력 메서드
    - 제약조건)
      - 여러명인 경우 `,` 으로 출력

## 기능 구현 체크리스트

- [x] 입력모듈
  - [x] 문자열 입력 파싱함수
    - 제약조건)
      - [x] `@woowacourse/mission-utils` 에서 제공하는 `Console.readLineAsync()` 활용하기
      - [x] `,` 으로 자동차 이름 구분
- 자동차 클래스
  - [ ] 자동차 이름 유효성 검사 함수
    - 제약조건)
      - [ ] 이름이 비어있으면 안됨
      - [ ] 각 이름은 5자를 초과할 수 없음
  - [ ] 전진가능여부 확인하는 메서드
  - [ ] 전진횟수 증가하는 메서드
- 경주 클래스
  - [ ] 경주 초기화 메서드
  - [ ] 경주 시작 메서드
  - [ ] 각 자동차 별 전진횟수 업데이트
  - [ ] 차수별 실행결과 출력 메서드
  - [ ] 우승자 판별 메서드
  - [ ] 결과 출력 메서드
    - 제약조건)
      - [ ] 여러명인 경우 `,` 으로 출력
