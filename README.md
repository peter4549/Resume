# 김성주 SEONGJU KIM

## Education
동아대학교 전자공학과 졸업 (2013.03 ~ 2019.02)</br>
성도고등학교 졸업 (2010.02 ~ 2012.12)

## Papers
1. 3축 가속도 센서를 이용한 낙상 인지 및 사후처리 시스템</br>
https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE07614256&language=ko_KR&language=ko_KR#</br>

2. 자폐스펙트럼장애 영유아의 음성 특징에 관한 연구
https://github.com/peter4549/Resume/blob/main/papers/%EC%9E%90%ED%8F%90%EC%8A%A4%ED%8E%99%ED%8A%B8%EB%9F%BC%EC%9E%A5%EC%95%A0%20%EC%98%81%EC%9C%A0%EC%95%84%EC%9D%98%20%EC%9D%8C%EC%84%B1%20%ED%8A%B9%EC%A7%95%EC%97%90%20%EA%B4%80%ED%95%9C%20%EC%97%B0%EA%B5%AC.pdf

## Android Applications
### 비디오 다이어리
유튜브 비디오를 다이어리에 등록하고 그에 따른 내용을 작성할 수 있는 애플리케이션.
### Features
1. 유튜브 비디오 가져오기</br>
구글 계정을 통하여 OAuth2 인증 토큰을 유튜브 데이터 API로 요청
![splash](Resume/images/youtube-diary/splash.jpb)
수신한 토큰을 사용하여 유튜브 Access code를 요청 </br>
수신한 Access code와 함께 YouTube Data API로 채널 정보를 요청하면 해당 계정의 유튜브 계정(브랜드 계정 포함)을 수신합니다.</br>
채널 정보를 수신했으니 플레이리스트 및 자신이 등록한 비디오에 접근할 수 있습니다.
#### Dependencies
Retrofit2</br>
Coroutines Adapter</br>
