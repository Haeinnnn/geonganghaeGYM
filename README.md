# 건강해GYM

안녕하세요! 팀 건강해GYM입니다.:smiley:

## 프로젝트명
건강해GYM (딥러닝을 통해 자세를 교정시켜주는 운동 영상 추천 프로그램)

## 프로젝트 개발배경 및 목적
각종 스마트 기기들을 사용하며 몸의 자세가 망가지고 있는 현대인들을 위해 AI 프로그램으로 집에서도 간단하게 본인의 사진으로 자신의 자세를 진단하고 혼자서도 교정을 도와줄 수 있도록 Youtube 영상을 추천해준다.

## 개발환경 및 개발언어

| 구분 | 항목 | Version |
| ------ | -- |----------- |
| 딥러닝 모델 구축 (Google Colaboratory 활용) |  CPU | Intel(R) Core(™) 2.40GHz |
|  | GPU | NVIDIA GeForce MX450 |
|  | Language | Python 3.7.13 |

## 시연 영상
- https://www.youtube.com/watch?v=6UIH4KeQd5U
- https://github.com/Haeinnnn/geonganghaeGYM/blob/main/%EC%99%84%EB%A3%8C%EB%AC%B8%EC%84%9C/%EA%B1%B4%EA%B0%95%ED%95%B4GYM_PPT.pptx

## 시스템 구성 및 아키텍처
![제목 없는 프레젠테이션 (1)](https://user-images.githubusercontent.com/67837142/190217508-29b11648-77e6-45b5-889d-f5aec84fad42.jpg)

#### 데이터 마이닝
![unnamed (7)](https://user-images.githubusercontent.com/67837142/190218706-561f43f6-5e81-4825-a645-70fe6af3a95d.png)

## 실행 코드 (데이터 폴더에 있는 데이터들 사용)
#### 이미지 처리(cutting) 및 CNN
* GYM_0915_STAND.ipynb [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Haeinnnn/geonganghaeGYM/blob/main/%EC%99%84%EB%A3%8C%EC%BD%94%EB%93%9C/GYM_0915_STAND.ipynb)
* GYM_0915_SIT.ipynb
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Haeinnnn/geonganghaeGYM/blob/main/%EC%99%84%EB%A3%8C%EC%BD%94%EB%93%9C/GYM_0915_SIT.ipynb)

#### 모델 실행 코드
* GYM_0915_Result.ipynb [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Haeinnnn/geonganghaeGYM/blob/415ba942efd843c47f2acabc87bc330d2b9a2671/%EC%99%84%EB%A3%8C%EC%BD%94%EB%93%9C/GYM_0915_Result.ipynb)

## 프로젝트 주요기능
- 사람이 앉거나 서있는 이미지를 통해 자세를 판단 
- 좋지 않은 자세(bad)로 판별되면 유튜브를 통해 자세 교정 영상과 해당 자세가 유발할 수 있는 질병과 관련된 영상을 추천

## 기대효과 및 활용분야
-  평소 자신의 앉은 자세와 서있는 자세를 촬영하여 활용하는 것이기 때문에 개인의 자세 습관 개선에 도움
- 개인의 평소 자세가 어느 정도로 좋고 나쁜지에 대한 객관적 지표를 제시해 주고 올바른 자세로 교정할 수 있는 추천 영상을 뜨게 하여 사용자의 자세를 교정
- 해당 모델을 개선하면 의료 기관에서 자세 판별 및 질병 예측 용도로 사용 가능

## 기타 (참고 사이트)

- YOLO: Real-Time Object Detection https://pjreddie.com/darknet/yolo/

## 팀원 정보 

| 구분 | 팀원 | 이메일 | 깃허브 주소 |
| ---------- | ---------- | ---------- | ---------- |
| 팀장 | 김해인 | eeheainee@gmail.com | https://github.com/Haeinnnn |
| 팀원 | 황서경 | peng5398@gmail.com | https://github.com/Hwang-sg |
| 팀원 | 이혜은 | heyeun9858@gmail.com | https://github.com/thewLHE |
| 팀원 | 이가은 | q40028qq@naver.com | https://github.com/chashudong |

## 프로젝트 개발 일정

| 주차 | 날짜 | 개발 내용 |
| ------ | -- |----------- |
| 1주차 | ~8/12 | 주제선정 및 데이터 수집 |
| 2주차 | ~8/19 | 데이터 전처리 |
| 3주차 | ~8/26 | 데이터 분석 |
| 4주차 | ~9/2 | 딥러닝 학습 및 구현 |
| 5주차 | ~9/5 | 테스트와 모델 보완 |
