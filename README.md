# 건강해GYM

안녕하세요! 팀 건강해GYM입니다.:smiley:


### 팀 회의 시간 : 평일 4-5시 (필참)

### 주 1회 오프라인 요일 : 금요일

### 멘토링 : 매주 토요일 11시 30분


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

## 시스템 구성 및 아키텍처
![제목 없는 프레젠테이션 (1)](https://user-images.githubusercontent.com/67837142/190217508-29b11648-77e6-45b5-889d-f5aec84fad42.jpg)

#### 이미지 처리(cutting)
![unnamed](https://user-images.githubusercontent.com/67837142/190217871-3a9c197c-1d5b-4c03-8987-975f79a0128c.png)
#### 이미지 csv처리
![unnamed (1)](https://user-images.githubusercontent.com/67837142/190217918-0520a170-3f2a-4424-8377-a668769dc4a3.png)

![unnamed (2)](https://user-images.githubusercontent.com/67837142/190217945-9890da9a-dd32-46f3-a29b-700aab2bff0d.png)

#### kmeans를 이용한 군집 분석을 시행하여 의미 있는 군집도출 가능 여부 확인
- kmeans sit 분류기준 3 최대 오차율 12% 정답율 88%
![unnamed (3)](https://user-images.githubusercontent.com/67837142/190218462-848d39bf-e70f-4f2e-922e-405a466efaa2.png)

![unnamed (4)](https://user-images.githubusercontent.com/67837142/190218513-dab2868b-9d9f-4c46-afa1-c6269adc630b.png)

- kmeans stand 최대 오차율 24% 정답율 76%
![unnamed (5)](https://user-images.githubusercontent.com/67837142/190218646-befde3ac-b262-4a4e-925f-9beaaafd73c8.png)
![unnamed (6)](https://user-images.githubusercontent.com/67837142/190218670-1fede80f-99ab-492f-bd6a-2b7c7c5b2ad4.png)

#### 데이터 마이닝
![unnamed (7)](https://user-images.githubusercontent.com/67837142/190218706-561f43f6-5e81-4825-a645-70fe6af3a95d.png)

## 프로젝트 주요기능
- 사람이 앉거나 서있는 이미지를 통해 자세를 판단 
- 좋지 않은 자세(bad)로 판별되면 유튜브를 통해 자세 교정 영상과 해당 자세가 유발할 수 있는 질병과 관련된 영상을 추천

## 기대효과 및 활용분야
-  평소 자신의 앉은 자세와 서있는 자세를 촬영하여 활용하는 것이기 때문에 개인의 자세 습관 개선에 도움
- 개인의 평소 자세가 어느 정도로 좋고 나쁜지에 대한 객관적 지표를 제시해 주고 올바른 자세로 교정할 수 있는 추천 영상을 뜨게 하여 사용자의 자세를 교정
- 해당 모델을 개선하면 의료 기관에서 자세 판별 및 질병 예측 용도로 사용 가능

## 기타(출품작에 대한 추가 설명 및 PT 자료 등 첨부 가능)

- YOLO: Real-Time Object Detection
https://pjreddie.com/darknet/yolo/

## 팀원 정보 

| 구분 | 팀원 | 깃허브 주소 |
| ---------- | ---------- | ---------- |
| 팀장 | 김해인 | https://github.com/Haeinnnn |
| 팀원 | 황서경 | https://github.com/Hwang-sg |
| 팀원 | 이혜은 | https://github.com/thewLHE |
| 팀원 | 이가은 | https://github.com/chashudong |

# 삭제할지 논의

## 프로젝트 개발 일정

| 주차 | 날짜 | 개발 내용 |
| ------ | -- |----------- |
| 1주차 | ~8/12 | 주제선정 및 데이터 수집 |
| 2주차 | ~8/19 | 데이터 전처리 |
| 3주차 | ~8/26 | 데이터 분석 |
| 4주차 | ~9/2 | 딥러닝 학습 및 구현 |
| 5주차 | ~9/5 | 테스트와 모델 보완 |
시간이 남으면 Youtube 영상 실시간 추천,
앱이나 홈페이지 제작을 목표로 한다.

<p>

* GYM_v2_5_20220826gn_ori_delete.ipynb
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Haeinnnn/geonganghaeGYM/blob/main/%EC%BD%94%EB%93%9C/GYM_v2_5_20220826gn_ori_delete.ipynb)
 
<p>
<p>
 
 
* openpose 템플릿
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/2022_WISET/blob/main/material/deep_learning/open_pose_using_template.ipynb)
 
<p>

<p>
 
 
* STAND0830 분류
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Haeinnnn/geonganghaeGYM/blob/main/%EC%BD%94%EB%93%9C/220830GYM_v3_2.ipynb)
 
<p>
