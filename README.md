## 현재의 목표

JavaScript 기초~고급 다지기.
현재 Study를 진행 중이며, 진행된 사항은 다음과 같음.

1. JavaSCript EcmaScript2020 강의 (21.02.14~)
2. JavaScript algorithm 100제 예정 (21.02.21~)

### 21.02.26

숫자 야구 구현 완료

1. 각 자리 숫자가 겹치지 않는 랜덤한 숫자 4자리 구현
2. 자리 수가 맞을 경우 strike, 맞지 않을 경우 ball, 숫자가 없을 경우 넘어가는 기능 구현
3. 정답을 맞출 시, 시작 버튼을 클릭 시 초기화 구현.

### 21.02.21

계산기 구현 완료

1. mozilla MDN 설명 상 eval은 caller의 권한으로 실행시키므로 상당히 위험하기에, 대체 함수로 구현.
2. 초기화 버튼 구현.

### 21.02.20

강의와 다른 방향으로 독자적으로 logic 설계, 계산기 구현 성공. -구현 사항

1. 버튼 구현
2. 단순 식이 아닌, eval 함수를 통한 계산 구현.
3. 예외 처리 - Number.parseInt()를 통해 만약 계산 식에 다른 글자가 들어갈 시, alert return

-미구현 사항

1. 괄호 식에 따른 오류 발생 부분은 고려하지 못함. ex) 1)+2, 2()
2. 초기화 미구현

### 21.02.19

미션인 계산기 구현에 앞서, css grid 연습 할 겸 전반적인 레이아웃 구성. -미구현: grid 정렬 부분.

### 21.02.16

Study 과제인 zeroCho 동영상 중 2강을 완독하며, 미션인 끝말잇기 프로그램 구현.

- 추가 기능

1. 중복 값 제거
2. 미입력 값 알림 창 경고 후 재개

### 21.02.15

Study 과제인 zeroCho 동영상 중 1강을 완독하며, 미션인 구구단 구현.

- 추가 기능

parseInt를 통한 예외 string 값 -> false 처리
