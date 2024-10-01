<div align="center">
  <img src="https://github.com/user-attachments/assets/77b3cdcb-9619-40ef-9497-48eba17b5a5f" />
  <h2>Custom Standard</h2>
  <p>주문 제작 상품을 사고 파는 거래 서비스</p>
</div>

## 🥄 소개
**Custom Standard** 는 주문 제작 상품을 사고 파는 거래 서비스를 제공합니다.

거래자 간 원활한 소통을 제공하여, 더 나은 주문 제작 상품을 거래할 수 있도록 돕습니다.

판매자뿐만 아니라 구매자도 글을 게시할 수 있어, 능동적인 주문 제작 거래가 가능합니다.

<br/>

## 🥄 기술 스택
### ✦ Frontend
<div>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/tailwind css-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
  <img src="https://img.shields.io/badge/shadcn/ui-000000?style=for-the-badge&logo=shadcnui&logoColor=white">
</div>

### ✦ Backend
<div>
  <img src="https://img.shields.io/badge/spring boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white">
  <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
</div>

### ✦ ETC
<div>
  <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/amazon ec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white">
  <img src="https://img.shields.io/badge/amazon s3-569A31?style=for-the-badge&logo=amazons3&logoColor=white">
  <img src="https://img.shields.io/badge/amazon rds-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white">
</div>

<br/>

## 🥄 제공 서비스
### • 간편한 소셜 로그인 (카카오 / 네이버 / 구글)
사용자가 더 편리하게 서비스를 이용할 수 있도록, 소셜 로그인 기능을 제공합니다.

OAuth2를 이용한 인증을 통해 카카오, 네이버, 구글의 소셜 로그인을 구현하였습니다.

<hr/>

### • 주문 제작 상품 거래글 작성
일반적인 주문 제작 상품 거래는, 구매자가 판매자를 찾아 원하는 상품을 요청하는 방식으로 이루어집니다.

이 프로젝트에서는 판매자뿐만 아니라 구매자도 거래글을 게시할 수 있어, 양방향 상품 거래가 가능하도록 설계되었습니다.

게시글에는 **예상 금액**과 **거래하고자 하는 날짜**의 리스트, 원하는 **상품 정보**(글, 사진 등)를 게시할 수 있습니다.

<hr/>

### • 거래글에 대한 주문 요청

사용자는 다른 사용자의 판매 또는 구매 게시글에 대해 주문 요청을 할 수 있습니다.

판매 게시글에는 구매 의사를, 구매 게시글에는 판매 의사를 표현할 수 있습니다.

판매자에게 원하는 형태의 프로토타입을 제안하거나, 구매자에게 자신의 예시 작품을 제공하기 위해 메시지와 사진을 추가로 첨부할 수 있습니다.

주문 요청 시, 게시글에 기재된 날짜에 한해서만 선택할 수 있도록 구현되었습니다.

주문은 **요청 중** - **준비 중** - **제작 중** - **제작 완료**의 단계로 진행됩니다. 

<hr/>

### • 진행중인 거래에 대한 제안

사용자 간 주문이 성립된 이후, 거래 날짜 및 가격, 상품에 대한 의견을 조율하기 위해 "제안" 기능을 제공합니다.

제안은 주문의 **준비 중** 단계에서만 가능하며, 날짜와 가격, 상품에 대한 조율이 완료되면 **제작 중** 단계로 넘어갈 수 있도록 설계되었습니다.

<hr/>

<!--
### 완료된 거래에 대한 리뷰 작성
### 활동에 대한 알림 전송
### 사용자 간 채팅 서비스
### Admin 서비스
-->
