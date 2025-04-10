# portfolio
💡 [ Protfolio Project 000 ] 소프트웨어 신입 개발자 🌱 박서연의 포트폴리오 입니다!  
  
  
## 📌 Intro
안녕하세요. 소프트웨어 개발자를 꿈꾸는 박서연입니다.  
- 이메일: syys10280@naver.com
- 블로그: https://velog.io/@tjdus1028
- 깃헙: https://github.com/syys1028
   
     
## 📌 Project
### 🔖 Python + Node.js + Express
#### 1. [(팀 프로젝트) 멀티모달 장면 검색 시스템](https://github.com/syys1028/2024-Multimodal-Scenes-Search)
>* 개요 : OTT와 VOD 서비스에서 사용자가 특정 장면을 쉽게 검색하고 다시 볼 수 있도록 멀티모달 기술을 활용한 시스템을 개발했습니다. 동영상에서 자막, 음성, 장면을 분석하여 텍스트로 추출하고, 이를 통해 키워드를 검색하면 영상과 타임스탬프를 제공해 해당 장면을 재생할 수 있습니다. 이 시스템은 다양한 검색 조건(장소, 인물, 자막 등)을 사용하여 동영상을 효율적으로 탐색할 수 있게 합니다.
>
>* 개발 기간 : 2024.08.23 ~ 2024.08.25, (update 2024.09)  
>
>* 개발 기술 및 도구 : 
>
>    - 장면 분석 : Python / Jupyter Notebook, Visual Studio Code / MySQL / OpenCV, PaddleOCR, Whisper, Place365, YOLOv8, Google Cloud API (Speech-to-Text, Translate)
>
>    - 웹 페이지 : HTML, CSS, JavaScript / Visual Studio Code / Node.js, Express, PHP
  
  
### 🔖 JAVA + Spring (Web)
#### 1. [(백엔드 로드맵 스터디) 감성 커뮤니티 제작 프로젝트](https://github.com/syys1028/Board-Service.git)
>* 개요: 하늘 사진, 위시리스트, 음악 공유, 짧은 한줄 기록 등 일상의 소소한 행복을 카테고리별로 공유하고, 감정 태그를 통해 공감하는 감성 기반 커뮤니티입니다. 로그인, 마이페이지, 좋아요, 댓글, 이미지 업로드, 태그 검색 기능까지 구현했습니다.
>  
>* 개발 기간: 2025.02 ~ 진행 중
>  
>* 개발 기술 및 도구: Java / Spring Boot / Spring Data JPA / QueryDSL / Spring Security / JWT / MariaDB / AWS S3 / Gradle / IntelliJ
>  

#### 2. [멀티모달 장면 검색 시스템 Spring 리팩토링 프로젝트](https://github.com/syys1028/2025-Refactoring-Multimodal-Scenes-Search-Public.git)
>* 개요 : 기존 Node.js + Express로 구현한 멀티모달 장면 검색 시스템을 Spring Boot 기반으로 리팩토링한 프로젝트입니다. 영상에서 자막, 음성, 장소 정보를 분석해 특정 장면을 검색할 수 있는 시스템으로, 기존 Node.js + Express 기반 서버를 Spring Boot로 전환해 회원별 데이터 관리와 검색 기능을 구현했습니다.
>  
>* 개발 기간 : 2025.01 ~ 진행 중
>  
>* 개발 기술 및 도구 : Java / Spring Boot / Spring Security / JWT / MySQL / Gradle / IntelliJ
>  

### 🔖 JAVA (Android)
#### 1. [모바일 미니 게임 제작 프로젝트](https://github.com/syys1028/Android-Mini-Game)
>* 개요: 센서 인식을 바탕으로 사용자가 네모 안에 공을 넣어 다음 단계로 넘어가는 모바일 게임입니다. 각 레벨에서 공과 네모의 크기, 속도가 변화하며, 하드 모드에서는 사라지는 공과 네모 등의 요소로 난이도가 증가합니다.
>
>* 개발 기간: 2023.09.18 ~ 2023.09.27
>
>* 개발 기술 및 도구: Java / Android Studio / SensorManager, Canvas, MediaPlayer, CountDownTimer

#### 2. [위치기록 앱 제작 프로젝트](https://github.com/syys1028/Location-Recording-App)
>* 개요 : 사용자의 위치를 기록하고 구글맵을 통해 이동 경로를 시각적으로 보여주는 위치 기록 앱을 개발했습니다. 사용자는 날짜별 이동 기록을 확인할 수 있으며, 웹 호스팅을 이용해 위치 데이터를 MariaDB에 저장하고 관리했습니다. 백그라운드 위치 추적과 경로 검색 기능도 구현했습니다.
>
>* 개발 기간 : 2023.10.30 ~ 2023.12.10
>
>* 개발 기술 및 도구 : Java / Android Studio / SQLite / iwinv 웹 호스팅, MariaDB, phpMyAdmin / PHP / Google Maps API / Geocoder
>

#### 3. [(팀 프로젝트) 교통 장애 경고 내비게이션 제작 프로젝트](https://github.com/syys1028/2023-Traffic-Warning-Navigation)
>* 개요 : 주행 중 도로의 위험 요소(공사현장, 장애물, 낙석, 포트홀, 블랙아이스 등)를 감지하여 실시간으로 사용자에게 경고하는 내비게이션 시스템입니다. 이 시스템은 Jetson을 사용하여 카메라로 촬영된 도로의 위험 요소를 데이터베이스에 저장하고, 그 데이터를 기반으로 지도의 해당 위치에 위험 요소를 표시하며, 위험 요소에 접근할 경우 음성으로 경고합니다.
>
>* 개발 기간 : 2023.08.25 ~ 2023.08.27
>
>* 개발 기술 및 도구 : Java / Android Studio / MariaDB, phpMyAdmin / Kakao Map API / Text-to-Speech (TTS) 
>

### 🔖 C, C++
#### 1. [술 취한 사람 길찾기 게임 프로젝트](https://github.com/syys1028/Drunk-Man-Game)
>* 개요 : 술에 취한 사람이 집으로 가는 여정을 자동 및 수동 이동 모드로 시뮬레이션하는 게임입니다. 자동 이동 모드와 수동 이동 모드를 통해 이동하며, 술집에서 시작해 경찰과 저격수 등의 방해를 피해 안전하게 집으로 돌아가는 것이 목표입니다.
>
>* 개발 기간 : 2022.11.16 ~ 2022.12.01
>
>* 개발 기술 및 도구 : C / Visual Studio 2019

#### 2. [소켓 기반 멀티유저 도서 관리 시스템](https://github.com/syys1028/Socket-based-Multi-User-Book-Management)
>* 개요 : 소켓 프로그래밍을 이용하여 다중 사용자가 동시에 접속하여 도서 정보를 관리할 수 있는 시스템을 구현하였습니다. 사용자는 회원 가입, 로그인, 도서 정보 조회, 추가, 수정, 삭제 등의 기능을 이용할 수 있습니다.
>
>* 개발 기간 : 2022.11.09 ~ 2022.12.15, (update 2024.09)
>
>* 개발 기술 및 도구 : C / Ubuntu Linux (Oracle VM VirtualBox) / 소켓 프로그래밍 (TCP/IP), 멀티프로세싱 (fork 함수)

#### 3. [퀸-맥클러스키 구현 프로그램](https://github.com/syys1028/Quine-McCluskey)
>* 개요 : 부울 함수를 최소화하기 위한 퀸-맥클러스키 알고리즘을 구현한 프로그램입니다. \n 사용자가 최소항을 입력하면 프로그램이 이를 분석하여 간소화된 논리식을 출력합니다.
>
>* 개발 기간 : 2023.05.26 ~ 2023.06.09
>
>* 개발 기술 및 도구 : C++ / Visual Studio 2019 / 퀸-맥클러스키 알고리즘
  
  
### 🔖 Python
#### 1. [RSA 구현 프로그램](https://github.com/syys1028/RSA-project)
>* 개요 : RSA 암호화 알고리즘을 구현하고, 입력한 텍스트 메시지를 암호화 및 복호화하는 프로그램입니다.
>
>* 개발 기간 : 2021.10.15 ~ 2021.10.30, (update 2024.09)
>
>* 개발 기술 및 도구 : Python / PyCharm / RSA 암호화 알고리즘
   
#### 2. [사용자 맞춤형 광고 추천 프로젝트](https://github.com/syys1028/Ad-Recommand-Project)
>* 개요: 사용자 정보(성별, 연령대, 관심 상품)와 구매한 상품 이미지를 분석하여 맞춤형 광고를 추천하는 시스템을 구현하였습니다. CNN을 이용한 이미지 분류 모델을 통해 구매한 상품을 분류하고, 입력한 정보를 활용해 사용자에게 적합한 광고를 제공합니다.
>
>* 개발 기간: 2022.06.08 ~ 2022.06.22, (update 2024.09)
>
>* 개발 기술 및 도구: Python / Spyder (anaconda3) / TensorFlow, Keras, OpenCV, CNN

