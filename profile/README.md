# Gachicar-SERVER
- 가치 있게 같이 쓰는 '가치카' 애플리케이션
- 숙명여자대학교 IT공학전공 졸업프로젝트
- 개발 기간: 2023.09 ~ 2024.04
<br/>
<p align="center">
  <img src="https://github.com/Gachicar/Gachicar-SERVER/assets/82032452/82a7ab69-5d6e-40e2-8dc7-b324011fa223" width="200" align="center" />
</p>

<br/>

## 📌 About This Project
그룹을 만들고 개인이 공유할 차량을 등록하여 그룹원들과 편리하게 공유하는 플랫폼입니다. 
음성비서를 사용하여 편리하게 공유 차량을 사용하거나 예약할 수 있으며, 홈 화면 및 메뉴에서 주행 리포트와 예약 리스트, 차량 정보 등을 조회할 수 있습니다.

<br/>

## 📌 Main Features

### 1️⃣ 그룹 및 차량 등록
- 회원가입/로그인 -> 그룹 생성 -> 차량 등록 -> 멤버 초대
- 그룹원들끼리만 해당 그룹의 공유 차량 이용 가능

### 2️⃣ 차량 이용 예약
- 음성 비서를 사용하여 목적지, 사용 일시, 이용 시간을 입력하면, 인공지능 서버에서 자연어 처리를 통해 사용자의 의도에 맞는 응답을 백엔드 서버에 전달
- 백엔드 서버에서는 해당 내용을 기반으로 기존의 예약 내역과 중복되지 않도록 유도하여 예약을 진행
- 공유 차량의 예약 리스트를 조회 가능
- 예약 시간에 사용 시간이 되었다는 알림 전송

### 3️⃣ 음성 인식 기반 공유 차량 이용
- 공유 차량을 사용하고 있는 사용자가 없는 경우, 음성 비서를 통해 목적지를 지정하여 즉시 차량 이용 가능
- 주행 중에는 다른 그룹원들이 해당 차량 이용 불가
- 주행이 종료되면 주행 리포트가 생성되고, 그룹원들은 공유 차량의 상태와 주행 리포트 리스트 조회 가능

<br/>

## 📌 Architecture
<img width="1801" alt="Architecture" src="https://github.com/Gachicar/Gachicar-SERVER/assets/82032452/25a1e334-cb6c-4fd5-9a6a-ab2c9d6da2ca">

<br/>

<br/>
## 📌 Execution Screen
- 어플 실행 화면
![Screenshot_20240319-194325_GachiCar](https://github.com/Gachicar/.github/assets/88912947/472ea7f6-cc48-4ca2-955c-16dcc40cdd7a)
![Screenshot_20240319-194910_GachiCar](https://github.com/Gachicar/.github/assets/88912947/494c8db9-1421-4931-9a31-d4e671c4d37a)
<br/>

## ⚙️ Stacks

  ### Environment
  <div>
    <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
    <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
    <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
    
  </div>
  
  ### Development
  | Part | Stack |
  | ---- | ----- |
  | Front-end | <img src="https://img.shields.io/badge/android-34A853?style=for-the-badge&logo=android&logoColor=white"><img src="https://img.shields.io/badge/kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"> |
  | Back-end | <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> |
  | AI | <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> |
  | AI AutoCar | <img src="https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"><img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">

  ### Communication
  <div>
    <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
    <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
  </div>

  <br/>
  
