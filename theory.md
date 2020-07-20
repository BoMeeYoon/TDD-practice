# TDD practice

---

<br/>

- js 문제점:
  - 실행시점에서 error 확인
  - data type <br/>
    🤔 다른 언어(예: JAVA)처럼 컴파일러가 없으니 `테스트주도개발(TDD)`이 필요하다!
    <br/>

## 1. 단위 테스트 (Unit Test)

- `단위(Unit)` : 특정 조건에서 어떻게 작동해야 할지 정의한 것 (예: 함수)
  - 3단계: 준비 -> 실행 -> 단언(return)
- 기능을 테스트할 수 있는 코드 만들기! (`RED`)
- 기능 구현하기! (`GREEN`)
- 추상화, 재사용성 높은 코드를 `REFACTORING - BLUE` 하기
- 함수는 하나의 기능만!

## 2. 테스트 환경 조성

- 테스트 프레임워크 : JASMINE
- 설치 방법:
  * Standalone(스탠드얼론): 테스트 결과만 간단하게 확인
  * Karma(카르마) 라이브러리와 연동(자동화)
- Standalone 방식: https://github.com/jasmine/jasmine/releases
