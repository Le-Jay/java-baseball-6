구현할 내용

1. 컴퓨터가 랜덤한 값(123 ~ 999) 생성. 단 같은 숫자나 0이 포함되면 안됨
2. 사용자의 입력을 받아 사용자 입력을 저장
    이때 사용자의 입력이 3자리가 아닌경우, 0이 포함된 경우, 같은 숫자를 중복해서 사용한 경우 예외처리 로직에 걸림
3. 사용자의 입력과 컴퓨터의 정답을 비교
4. 정답 비교 함수 구현. 자릿수 일치, 숫자 일치 = strike
    자릿수 불일치, 숫자 일치 = ball, 나머지 = "낫싱" 출력
5. 정답을 맞췄을 경우 종료 출력. 즉 자릿수 숫자 일치 count가 3이면 종료 출력
6. 종료 출력되었을때도 입력을 받을 수 있음. 1이면 과정 1부터 다시, 2이면 아예 종료
