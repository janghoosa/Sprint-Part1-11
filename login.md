# 숙박 업소 예약 어플
## 로그인
1. 사용자 아이디, 비밀번호 작성
2. 작성된 아이디, 비밀번호를 받아서 db와 대조
    - 비밀번호의 경호 복호화 또는 별도의 대조 로직 필요
3. 대조 결과 출력
## 회원가입
1. 아이디, 비밀번호, 개인정보 작성
    - 이름, 생년월일 등
    - 아이디의 경우 이메일로 받는다
    - 비밀번호의 경우 일정 길이 이상을 입력하도록 한다
2. 작성한 정보 db에 저장
    - db에 저장하기 전 유효성 검사를 한다
    - 유효성 검사를 통과하지 못하면 db에 저장하지 않는다
    - 비밀번호의 경우 암호화하여 저장한다
    - 저장 후 성공 여부를 출력한다

~~ 충돌 유도 시도 중~ ~~