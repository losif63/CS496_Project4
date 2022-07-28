# NewURS
> 2022 Summer MadCamp Week4 Class 2

## 1. Teammates ##

Developed by:
* KAIST 전산학부 20학번 [서재덕](https://github.com/losif63)
* KAIST 전산학부 19학번 [안태찬](https://github.com/antaechan)

Designed by:
* KAIST 배세윤

***

## 2. Development Info ##
* Language: HTML, CSS, JAVASCRIPT
* Framework: React
* Backend: Node.js + express
* Database: MariaDB

***

## 3. 웹페이지 정보 ##

* KAIST의 시설물들을 간편하게 예약할 수 있는 웹페이지입니다.
* 기존 URS 웹사이트의 UI를 개선하였습니다.

***

## 4. 예약 과정 ##

로그인 화면               |   회원가입 화면            
:-------------------------:|:-------------------------:
![Screen Shot 2022-07-28 at 6 35 49 PM](https://user-images.githubusercontent.com/77673334/181473901-1cdca173-0923-44a2-a37a-9f8b6c69c6e4.png) | ![Screen Shot 2022-07-28 at 6 37 49 PM](https://user-images.githubusercontent.com/77673334/181474190-a1f1a5b1-f1c0-4f90-811e-e44f68a40892.png)

* 계정이 존재할 경우, 이메일과 비밀번호를 이용하여 로그인할 수 있습니다.
* 계정이 없을 경우, 이메일과 비밀번호, 그리고 이름을 등록하여 계정을 생성할 수 있습니다.

나의 예약 화면 | 상세보기 화면
:-------------------------:|:-------------------------:
![Screen Shot 2022-07-28 at 7 16 29 PM](https://user-images.githubusercontent.com/77673334/181487425-b3408351-00b2-4f40-8569-f96c3b8e5dd7.png) | ![Screen Shot 2022-07-28 at 7 16 49 PM](https://user-images.githubusercontent.com/77673334/181487765-dc0a417c-3f46-465b-beb7-e3d001103b98.png)

* 나의 예약 현황을 확인할 수 있습니다.
* 현재 진행중인 예약, 미래에 진행 예정인 예약, 과거 예약으로 나뉘어 표시됩니다.
* 나의 예약 화면에서 예약 아이템을 클릭하여 상세보기 화면으로 넘어갈 수 있습니다. 상세보기 화면에서는 해당 예약을 취소할 수 있습니다.

예약하기 화면 | 예약 시설 선택 화면
:-------------------------:|:-------------------------:
![Screen Shot 2022-07-28 at 7 14 26 PM](https://user-images.githubusercontent.com/77673334/181488317-5ab3313b-cc1b-4d27-b8ba-0cdd12cc5543.png) | ![Screen Shot 2022-07-28 at 8 25 43 PM](https://user-images.githubusercontent.com/77673334/181494120-2a1353f0-1271-45f2-b5cc-1276c074da1b.png)


* 건물을 클릭하여 해당 건물 내 예약 가능 시설들을 조회할 수 있습니다.
* 예약 가능 시설을 클릭하면 해당 시설의 예약 현황을 조회할 수 있습니다.

예약 화면 |
:-------------------------:|
![Screen Shot 2022-07-28 at 8 45 58 PM](https://user-images.githubusercontent.com/77673334/181497612-7c18adb7-1004-4442-b2f3-c68fc132b5d1.png)

* 달력을 통해 날짜를 선택할 수 있습니다. 날짜를 선택하면 해당 날짜의 해당 예약 시설 예약 현황이 화면이 표시됩니다.
* 시작 시간과 종료 시간을 설정한 뒤 다음 버튼을 눌러 상세 정보 기입 화면으로 넘어갑니다.

상세 정보 기입 화면 | 예약 정보 확인 화면
:-------------------------:|:-------------------------:
![Screen Shot 2022-07-28 at 8 46 25 PM](https://user-images.githubusercontent.com/77673334/181501971-db1ce7ef-a009-4328-a02a-309823244738.png) | ![Screen Shot 2022-07-28 at 8 46 37 PM](https://user-images.githubusercontent.com/77673334/181501990-927e70c8-efff-4a86-9f8e-d1d8c39cce5b.png)

* 상세 정보 기입 화면에서는 다른 사람들에게 표시될 예약자명과 예약 사유를 적어야 합니다.
* 약관을 동의하여야 예약을 진행할 수 있습니다.
* 예약 정보 확인 화면에서는 기입한 예약 정보들을 재확인할 수 있습니다.


예약 완료 화면 |
:-------------------------:|
![Screen Shot 2022-07-28 at 9 14 23 PM](https://user-images.githubusercontent.com/77673334/181502379-eae5d413-d81d-47a6-abf0-457818c597f5.png)

* 예약 완료 화면입니다. 아래 확인 버튼을 눌러서 예약하기 메인 화면으로 돌아갈 수 있습니다.