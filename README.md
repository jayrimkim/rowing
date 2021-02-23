## V/AR 글래스와 어깨 스피커를 이용한 로잉머신 솔루션/한이음 멘토링 팀 프로젝트
팀 프로젝트로, <b>서버와 웹사이트,출석</b>을 담당했습니다. 

### 프로젝트 개요
![스크린샷](https://user-images.githubusercontent.com/79407445/108878098-3f311600-7643-11eb-8860-f3e8ce1068fe.png)
헬스 엔터테인먼트 로잉머신 기반 AR, VR 어플리케이션을 V/AR 글래스와 어깨 스피커와 함께 사용하여 생동감 넘치는 운동 환경을 제공한다.


작동 영상
<iframe width="560" height="315" src="https://www.youtube.com/embed/wL7urCvdEwQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

본 프로젝트는 V/AR 글래스 + 어깨 스피커 + 위치 센서(스마트 밴드 SDK 활용) + 시뮬레이션 엔진(Unity) + 5G + 로잉머신의 조합으로 AR 기반의 헬스 엔터테인먼트 조합으로 구성된다.

![설계도](https://user-images.githubusercontent.com/79407445/108876850-017fbd80-7642-11eb-9a0a-7e25f47f9eaf.png)

### 주요 기능
1) AP를 활용한 네트워크 제어 (값 전달, 여러 사용자와 공유)

2) 스마트 밴드 내의 자이로센서를 이용하여 사용자의 운동 거리를 측정하고 sdk를 이용하여 운동 데이터를 추출하여 사용한다.

3) 측정 운동 거리를 활용하여 칼로리 소모, 속도 등을 계산한다.

4) 이를 활용한 헬스테인먼트를 제공한다.

5) 로잉머신과 HMD 등을 이용한 물리적 운동 도구를 제어한다.
