# MiseangProject
Scene Graph for Miseang(Drama)

- - -

## Project1 ✔
### 1. Introdcution
![MiseangProject](image/introduction.jpg)

* 심층 신경망 모델들로 부터 다양한 장면 구성 요소들 추출
* 사전에 정의해둔 온톨로지 스키마를 기반으로 장면 구성 요소들 사이의 관계를 정의하고 트리플 생성
* 생성된 트리플을 기반으로 장면 그래프 생성 


### 2. Video Demo
* Input Video
<center><img src="/image/scene5-11.gif" width="400" height="250"></center> 

* Scene Graph
<center><img src="/image/graph5-11.gif" width="400" height="250"></center>


- - -

## Project2 ✔
### 1. Introduction
![MiseangProject](image/introduction2.jpg)
* 관계를 온톨로지 스키마에 기반하여 정의하는 방식이 아닌 신경망으로 인식
* 이를 위해 새로운 스키마를 가지는 총 836개의 “Miseang-VidSG” 데이터 집합 생성


### 2. Dataset Structure
![MiseangProject](image/dataset.jpg)
* subject / object: 물체 id와 카테고리
* trajectories : 각 프레임마다 등장 물체들의 id와 바운딩 박스의 위치(xmin, ymin, xmax, ymax)
* relation : 주어와 목적어 물체의 id, 관계 카테고리, 관계의 시작 프레임과 끝 프레임 


