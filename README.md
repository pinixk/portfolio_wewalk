# WEWALK APP
![image](https://github.com/user-attachments/assets/f9d6e005-a20a-406c-9346-c12f6cdb9e20)


- 어플리케이션 : [IOS](https://apps.apple.com/kr/app/%EC%9C%84%EC%9B%8C%ED%81%AC/id1586091495) / [Android](https://play.google.com/store/apps/details?id=com.inplusweb.wewalk&hl=ko)
- Test ID : bjkim0110@gmail.com
- Test PW : !123

<br>

## 앱 소개

- QR인증 기반의 걷기 챌린지
- QR의 500m 이상에서는 인증 불가

<br>

## 목표
- **기존 PHP기반의 웹앱형태의 앱에서 Flutter, Java Spring boot를 활용한 네이티브 앱으로 전환**
 
<br>

### 개발 환경

- Front-end : Flutter
- Back-end : Java Spring boot
- 버전 및 이슈관리 : Git, CodePipeline, Elastic Beanstalk
- 협업 툴 : GitLab, Excel
- 서비스 배포 환경 : AWS
- DB : MySQL, AWS RDS, S3

<br>

### 마일스톤
- **2024년 11월 - 2024년 12월**
    - 기존 앱 기술 파악
    - DB 파악
    - 서버 AWS로 이전 준비
    - Java Spring boot 공부

- **2025년 12월 - 2025년 2월**
    - 필수적 데이터 DB 이전
    - 기존 UX/UI를 최대한 살리되 개선
    - QR 정확도 향상

<br>

## 화면구성

### [초기화면]
- 서비스 접속 초기화면으로 splash 화면이 잠시 나온 뒤 초기 페이지
    - 로그인이 되어 있지 않은 경우 : 로그인 화면
    - 로그인이 되어 있는 경우 : 홈 화면

| 초기화면 |
|----------|
|![splash](https://github.com/user-attachments/assets/99a9f4f2-09b1-4a71-bb22-1b7e4a429943)|


### [회원가입]
- 회원권의 타입에 따라 헬스 / 필라테스 구분되어 DB 저장
- 센터를 입력함과 동시에 해당 센터가 표시되어 선택
- 이름 / 비밀번호 / 생년월일 / 휴대폰번호 / 주소 입력
- Naver SMS API를 통한 휴대폰 인증(휴대폰 번호로 로그인 가능하도록 설정되어 있음)
- 도로명주소 API(juso.go.kr)를 통한 주소 검색

| 회원가입 |
|----------|
|![register](https://github.com/user-attachments/assets/50cdb372-d51b-44a7-af0a-75f681d1f15b)|


### [강사예약]
- 달력을 활용한 각 날짜별 강사님 스케일 표시
- 예약 / 대기 / 취소 기능
- 예약자가 한명 빠지면 대기사 1순위 회원님에게 문자 자동 전송

| 강사예약 |
|----------|
|![book](https://github.com/user-attachments/assets/263425f7-df7e-454a-b591-2af68c4c6dba)|


### [QR코드]
- QR코드를 활용한 회원님 출입 서비스 구현
- QR체크 시 회원님의 수업장소 안내

| QR코드 |
|----------|
|![qr](https://github.com/user-attachments/assets/2b35a5f1-1c65-4419-82d2-c155b53c4da6)|


### [회원권]
- 적용되어 있는 회원권 확인
- 회원권 기간 내 예약횟수 / 취소횟수 표시
- 현재 예약 중인 수업 / 대기 중인 수업 / 1:1 PT 현황 표시

| 회원권 |
|----------|
|![ticket](https://github.com/user-attachments/assets/0e8d074a-dcbc-49bf-93ca-0de038078f9d)|


### [일일기록]
- 현재 체중 / 운동 / 식단 / 수면 / 수분 기록
- 이미지 관리는 AWS의 S3로 관리
- 달력을 통한 본인의 일별 기록 열람

| 체중기록 |
|----------|
|![record-weight](https://github.com/user-attachments/assets/9e51c12f-ea32-44d7-b4b2-8d898ca8aa81)|

| 운동기록 |
|----------|
|![record-workout](https://github.com/user-attachments/assets/ffd8f5ca-20e8-4496-ad0c-d43d1cfa4624)|

| 식단기록 |
|----------|
|![record-diet](https://github.com/user-attachments/assets/c8c74cb4-d5dd-415c-a04f-778c3e77d44f)|

| 수면기록 |
|----------|
|![record-sleep](https://github.com/user-attachments/assets/de2811aa-88a1-4269-8073-bc767736af57)|

| 수분기록 |
|----------|
|![record-water](https://github.com/user-attachments/assets/99b6a6fc-f500-4373-9d98-d012485234d2)|

| 달력 |
|----------|
|![record-calendar](https://github.com/user-attachments/assets/77358857-6ada-4901-9a96-a9e04276e2bf)|


### [목표설정]
- 일일기록 / 목표기록 / 달성기록
- 일일 기록 확인 가능
- 회원님이 직접 한달간 목표를 설정 가능
- 한달 목표에 대한 기록 달성률을 바 그래프로 표현
- 선택 기간에 대한 달성률 선 그래프로 표현
- 연속 달성 횟수 표시

| 목표설정 |
|----------|
|![challenge](https://github.com/user-attachments/assets/1a5f1d6c-7421-4e46-ae8d-1d541a6367b6)|


### [프로필]
- 이름 / 생년월일 / 휴대폰번호 / 신체정보 표시
- 휴대폰번호 / 신체정보 수정 가능
- 프로필 사진 변경 기능

| 프로필 |
|----------|
|![mypage](https://github.com/user-attachments/assets/677baca5-ed7a-41b4-8192-188627da6f1f)|


### [Etc]
- 알림설정 / 공지사항 / 이용약관

| Etc |
|----------|
|![etc](https://github.com/user-attachments/assets/64b24c52-a361-4959-9143-e7578a3339f5)|

### [회원탈퇴]
- 회원탈퇴의 이유를 수집
- 실수로 탈퇴하는 것을 방지하기 위해 체크박스로 계정삭제 버튼 막아놓기

| 회원탈퇴 |
|----------|
|![resign](https://github.com/user-attachments/assets/afc84b09-8e86-4360-99b3-b1880c1eed2d)|
