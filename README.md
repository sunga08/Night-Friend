# 밤길 친구 안드로이드 앱
덕성여대 WISET ICT 팀프로젝트(2020)

## 개발 배경
- 목적 
    - 사용자가 늦은 밤에도 안전하게 귀가할 수 있도록 돕고, 익숙하지 않은 지역에 대한 정보를 파악하여 경계함으로써 범죄 예방의 효과를 제공하기 위함
    
- 특장점
    - 경로 안내시 안전을 우선시한 경로를 제시함으로써 기존 길찾기 서비스와 차별화
    - 이동 경로에 따른 사용자간 매칭 서비스 제공하여 동행할 수 있도록 함

## 프로젝트 개요
- 개발 기간 : 20.03 ~ 20.10 

- 개발 인원 : 4명

- 사용 언어 : Java, php

- 개발 환경 : Android Studio

- API 및 라이브러리
    - API : T Map API, 공공데이터포털 Open API, 안전 Dream API
    - 라이브러리 : tensorflow, firebase, volley, jackson
    
## 주요 기능
1. 안심지도 제공
    - CCTV, 가로등, 우범지역, 유흥업소 거리를 지도에 시각화하여 안전 관련 시설물의 위치를 파악할 수 있도록 함
    <div>
    <img width="200" src="https://user-images.githubusercontent.com/53103434/103452093-02b1ff80-4d0f-11eb-8edb-dc94debd9367.jpg">
    </div>
    
2. 안전지수를 적용한 경로안내 및 경로이탈 기능
    - 자체적으로 만든 안전지수 모델을 T Map 경로안내 API에 적용하여 안전 우선 경로 제공
    - T Map API의 옵션이 적용된 경로 외의 경로를 얻기 위해 임의 경로 생성
    - 사용자가 선택한 경로 이탈시 경고 후 신고 기능 작동
    <div>
    <img width="190" src="https://user-images.githubusercontent.com/53103434/103452377-ff6c4300-4d11-11eb-8bb5-59cb7253e876.jpg">
    <img width="200" src="https://user-images.githubusercontent.com/53103434/103452091-02196900-4d0f-11eb-93eb-18d938ee79e7.jpg">
    <img width="200" src="https://user-images.githubusercontent.com/53103434/103452463-22e3bd80-4d13-11eb-8ad8-2913e4f352d0.jpg">
    </div>
    
3. SOS 자동 신고 및 자동 녹화 기능
    - 사용자가 선택한 경로 이탈시 자동으로 보호자에게 위치가 포함된 메시지 전송 및 112 신고
    - 사용자가 원하는 경로를 선택하면 길 안내와 동시에 자동으로 녹화 진행
    <div>    
    <img width="200" src="https://user-images.githubusercontent.com/53103434/103452086-fcbc1e80-4d0e-11eb-96e7-44325ba81204.jpg">
    <img width="200" src="https://user-images.githubusercontent.com/53103434/103452092-02b1ff80-4d0f-11eb-9093-b9f5093e79b5.jpg">
    </div>
    
4. 매칭 서비스
    - 비슷한 경로를 가진 사용자를 추천하고, 사용자들을 지도에 나타내어 선택할 수 있도록 함
    <div>
    <img width="200" src="https://user-images.githubusercontent.com/53103434/103452090-00e83c00-4d0f-11eb-8817-8e74d3ef3256.jpg">
    </div>
    
5. 채팅 기능 제공
    - 매칭 서비스 이용시 선택한 사용자와 채팅 진행
    <div>
    <img width="200" src="https://user-images.githubusercontent.com/53103434/103452094-034a9600-4d0f-11eb-96e5-f2ab743c7e24.jpg">
    </div>
