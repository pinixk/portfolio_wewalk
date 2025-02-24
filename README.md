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
  - 참여인원 : 3명(CTO 1명, Back-end: 1명, Front-end: 1명)
 
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
|![splash](https://github.com/user-attachments/assets/9213bb5b-ecdc-49fe-9217-570f02967804)|


### [홈 화면]
- 현재 위치한 좌표 기반 날씨 표시
- 본인이 참여한 챌린지 표시
- 인증방법, 유의사항 등 명시
- 햄버거 네비게이터
- 현재, 전에 실시 했던 챌린지 리스트

| 홈 |
|----------|
|<img src="https://github.com/user-attachments/assets/d382fb77-faf0-4f45-94d0-e714b8c6b6cb" width="300"/>|


### [챌린지 메인]
- 챌린지 소개 탭
- 챌린지 QR 인증 횟수에 따른 리워드 신청, 주의사항
- 챌린지 코스 썸네일
- 게시판

| 챌린지 메인 |
|----------|
|<img src="https://github.com/user-attachments/assets/fa0f6060-b887-4cdc-b20b-df3fac1ff9b0" width="300"/>|


### [챌린지 코스]
- 간단한 챌린지 코스 썸네일 or 단계 구분
- 클릭 시 카카오맵을 활용한 위치 표시
- 핀 클릭시 사진과 간단한 설명
- QR코드를 활용한 위치 인증
- 인증 시 500m 이내가 아니라면 불가

| 챌린지 코스 |
|----------|
|<img src="https://github.com/user-attachments/assets/7048033f-d789-4242-b025-24119563f45e" width="300"/>|


### [챌린지 게시판]
- 사진 슬라이드
- 좋아요
- 댓글 CRUD

| 챌린지 게시판 |
|----------|
|<img src="https://github.com/user-attachments/assets/2221d901-1d01-4401-b361-7b35f38fba26" width="300"/>|


### [햄버거]
- 프로필 수정
- 공지사항, FAQ, 1:1문의
- 서비스 약관

| 햄버거 |
|----------|
|<img src="https://github.com/user-attachments/assets/11dc1f8a-adfa-4577-8586-686156fa6308" width="300"/>|
