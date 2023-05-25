# Dating App 💌
Flutter, Firebase 기반 데이팅 앱

##  팀 소개 👨‍👦‍👦
 ### JIN = 진실할 진(眞)
 각종 프사기와 포토샵이 난무하는 기존 데이팅 어플과는 다른,  
 자신과 상대방의 진실하고 진정한 모습을 나타내는 것을 추구하고자 하는 것을 의미합니다.
 ### 팀원 소개
  - 팀장 : 안주성(2018147597) - UI/UX
  - 팀원1: 김기영(2018147596) - Sign-In Function
  - 팀원2: 김명섭(2019147545) - User Profile Function
  - 팀원3: 조우현(2018147547) - User Profile Function
  - 팀원4: 강준서(2020147044) - UI/UX, Geolocation & Matching Function
  - 팀원5: 배성윤(2012147564) - Geolocation & Matching Function
  - 팀원6: 안태민(2020199013) - Chat Function
  - 팀원7: 최재혁(2013147507) - Settings Function
## 프로젝트 소개 🖥
 ### 기존 데이팅 어플의 문제점
 기존 데이팅 어플의 경우, 어플리케이션 모두 본인 카메라와 이미지 중 선택할 수 있게 설계되어 있습니다.  
 이는 과하게 보정된 모습에서부터 다른 사람의 사진을 무단 도용하여 사용하기도 합니다.  
 ### Dating App - JIN
 이에 착안한 아이디어로, JIN에서 개발한 데이팅 어플은 기기의 기본 카메라만 사용하여,  
 사진 필터 효과를 제거하고, 프로필 사기를 방지하며, 보다 신뢰성 있는 만남을 가능하게 하도록 구현되었습니다.  
 또한 필터링을 위해서 투자해야 하는 정신적인 스트레스가 감소할 수 있습니다.
 ### 개발 방법론
  * Scrum
  * Integration and Configuration
 ### 개발 기간
  - 22.10.01일 ~ 22.12.07일
 ### 개발 환경
  - `Dart 2.8.1`
  - `Flutter 1.17.0`
  - Firebase
  - Android studio
 ### Application Version
  - minSdkVersion : 21
  - targetSdkVersion : 33
  - compileSdkVersion : 33
 
 
## 주요 기능 🛠
 ### Sign in Process
 - Welcome page를 통해 로그인을 할 수 있다.  
 - 하단의 Sign Up Now를 통해 회원가입을 진행할 수 있다.  
![sign in progress](https://user-images.githubusercontent.com/63450075/205789962-061d738b-8446-4de6-b3bb-7ee7c4222cb0.png)
![sign in progress2](https://user-images.githubusercontent.com/63450075/205790024-33f1e195-3a60-4751-a2d1-46390087cdb6.png)  
***
 ### Geolocation Access
 - 사용자들이 현재 거주하는 위치를 access한다.  
 ![geolocation access](https://user-images.githubusercontent.com/63450075/205799491-5afc734b-6220-4644-a304-852d749483cc.png)
 ***
 ### Profile Setup
 - 사용자의 사진, 나이, 사용자의 성별, 원하는 성별을 선택하여 프로필을 생성한다.  
 ![profile setup](https://user-images.githubusercontent.com/63450075/205799835-f5b761ab-b970-4902-aab8-02985bea1d61.png)
 ![profile setup sample](https://user-images.githubusercontent.com/63450075/205817093-b2c89bbd-abad-42b9-b6c5-20fb025997f3.png)
 ***
 ### Match Process
 - 원하는 상대의 프로필을 선택하거나, 상대가 사용자의 프로필을 선택하게 된다.  
 - 이후, 매칭을 시켜준 뒤, 채팅할 수 있는 채팅방을 사용할 수 있다.  
 ![match process 1](https://user-images.githubusercontent.com/63450075/205821393-629da8e7-4722-4372-8d05-2952082b1ad1.png)
 ![match process 2](https://user-images.githubusercontent.com/63450075/205821456-31192f41-a1ca-4d46-a249-11b58144cf3e.png)
 ![match process 3](https://user-images.githubusercontent.com/63450075/205821483-5efec15f-5f28-4a61-94a3-b1dda67d177d.png)
 ***
 ### Chat Process 
 - 원하는 상대의 프로필을 선택하여, 채팅을 진행할 수 있다.  
![chat process 1](https://user-images.githubusercontent.com/63450075/205822169-8c264843-40b4-40e7-9b39-7e8f87ac8777.png)
![chat process 2](https://user-images.githubusercontent.com/63450075/205822201-ce76d067-d175-497a-a23e-b602421e8318.png)
