# 문자열 덧셈 계산기

### 기능 목록

- [x] 문자열을 입력받는다
- [ ] 문자열을 검증한다
    - [ ] `구분자`와 `양수`로 이루어지지 않았을 경우는 예외다
    - [ ] 커스텀 구분자가 지정된 경우, 다른 구분자가 존재하면 예외다
- [ ] 구분자 기준으로 분리하여 숫자를 추출한다
- [ ] 추출한 숫자의 합을 구한다
- [ ] 합을 출력한다

---

### 기능 요구사항

- [ ] 쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열을 전달하는 경우 구분자를 기준으로 분리한 각 숫자의 합을 반환한다.
- [ ] 앞의 기본 구분자(쉼표, 콜론) 외에 커스텀 구분자를 지정할 수 있다.
- [ ] 커스텀 구분자는 문자열 앞부분의 "//"와 "\n" 사이에 위치하는 문자를 커스텀 구분자로 사용한다.
- [ ] 사용자가 잘못된 값을 입력할 경우 `IllegalArgumentException`을 발생시킨 후 애플리케이션은 종료되어야 한다.