## 시작

- 1~9까지의 임의의 수 3개를 선택해서 저장하는 기능
- 시작할 때 숫자 야구 게임을 시작합니다를 출력하는 기능

## 실행

- 서로 다른 3자리의 수를 입력받는 기능
- 입력한 숫자와 컴퓨터의 숫자를 비교해서 볼과 스트라이크의 카운트를 세는 기능
- 볼과 스트라이크가 한개도 없는 경우 => 낫싱 출력
    - 스트라이크가 3개인 경우=> 게임종료
    - 그외 => 볼, 스트라이크 개수 출력
    - 게임이 끝난 경우 재시작, 종료를 구분해서 처리하는 기능

## 예외처리

- 잘못된 값을 입력한 경우 예외를 발생시키고 종료하는 기능
    - 숫자가 아닌 문자가 입력되었을때 에러 발생
    - 숫자의 길이가 3이 아닌 경우 에러 발생
    - 같은 숫자가 입력되었을때 에러 발생 