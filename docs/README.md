- 다리 만들기
    - 사이즈 벗어나면 에러
    - 사이즈만큼 업다운 리스트 만들기

- 랜덤으로 업다운 정하기
    - 랜덤으로 만들어진 수가 0이나 1이 아니면 예외처리

- 다리 사이즈 입력받기
    - 사이즈 입력받아서 int로 변환 안되면 예외처리

- 유저가 이동할 방향 입력받기
    - U,D 이외의 문자면 예외처리

- 해당방향으로 움직이기
    - 못움직이면(방향이 틀렸으면) 재시도 여부 묻기

- 재시도 여부 입력받기
    - 중간에 틀리면 재시도 여부 입력받기
    - Q,R 중에 하나가 아니면 예외처리
    - Q면 결과 보여주고 종료
    - R이면 이전 기록 초기화 하고 처음부터 다시 시도

- 결과 시각화하기
    - 실제 다리 모양과 유저가 걸어온 방향을 비교해서 시각화하기
