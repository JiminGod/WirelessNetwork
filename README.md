# 🏆무선네트워크 A반 3조 팀 프로젝트
라즈베리 파이, 카메라 센서를 활용한 얼굴인식 출결관리 시스템

## 프로젝트 소개
라즈베리 파이와 카메라를 통해 얼굴을 인식하고 데이터베이스에 저장되어있는 얼굴과 비교하여 일치할 시
출석체크가 되도록하는 출결관리 시스템을 개발합니다.

## 멤버구성
``` 
김지민, 이재윤, 유태영, 김강민, 구민규, 김현빈
```


## 구조
1. 라즈베리 파이 + 카메라 센서
2. 얼굴인식 모델
3. 사진 데이터베이스 저장 및 모델과 비교, 출석 체크
4. 출결관리 UI

## 주요기능

## 각 분야 기능

🔷 프론트엔드 (React - 라즈베리 파이에서 실행): 구민규, 유태영

- 리액트 앱을 개발하여 얼굴인식 출석부의 사용자 인터페이스를 담당합니다.
- 웹 페이지에서 카메라를 제어하는 버튼을 추가하고, 얼굴을 촬영하여 서버에 전송합니다.
- 서버로부터 얼굴인식 결과와 출석 정보를 받아와 UI에 표시합니다.


🔷 백엔드 ( ?? - 라즈베리 파이에서 실행): ?? , ??

-  ??  를 사용하여 라즈베리 파이에 서버를 구성합니다.
- 클라이언트의 요청을 처리하고, OpenCV를 사용하여 카메라로 촬영한 이미지를 얼굴인식 모델에 전달합니다.
- 출석 정보를 저장하고, 필요에 따라 데이터베이스를 사용하여 출석 기록을 관리합니다.
- OpenCV를 이용하여 라즈베리 파이의 카메라를 제어하고 얼굴인식 결과를 클라이언트로 반환합니다.

🔷 얼굴인식 AI 학습 (OpenCV - 서버 또는 외부에서 수행): 김재윤, ??

- OpenCV와 함께 Dlib 등의 라이브러리를 사용하여 얼굴 특징을 추출하고 학습 데이터를 구성합니다.
- 학습된 모델은 라즈베리 파이의 백엔드 서버로 전송되어 사용됩니다.
- 얼굴인식 AI 학습은 라즈베리 파이보다 높은 성능의 서버 또는 외부에서 수행됩니다.

#### 얼굴인식
- 얼굴 촬영 후 등록된 데이터베이스의 얼굴과 비교 후 관리자에게 촬영한 얼굴과 가장 비슷한 얼굴을 확인을 하여 출석체크
- 얼굴 인식이 힘들 시 지정되어있는 학번을 통해 로그인 하는 것도 가능

### ⏳프로젝트 진행상황
1. 참고자료 토대로 모델 학습(이미지 전처리) 진행 중


## 참고자료
- https://yunwoong.tistory.com/92
- https://wondangcom.tistory.com/2446
