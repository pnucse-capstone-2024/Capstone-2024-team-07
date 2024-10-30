# 질병 연관 유전자 발굴을 위한 머신러닝 기법 설계

## 1. 프로젝트 소개
### 1.1. 배경 및 필요성
> &nbsp;인간의 유전자에서 질병과의 관계를 파악하는 것은 질병의 발병가능성을 예측하고 초기에 대응하기 위해 중요한 생물학적 문제이다. 여러 임상 실험을 통해 유전자와 질병 간의 관계를 파악하거나 유전자 데이터 분석을 통해 유전자와 질병의 관계를 밝혀내기도 한다. 하지만 직접적으로 연관성을 찾아내는 방식은 분명히 한계가 존재하기 때문에 비교적 최근 연구에서는 유전자 간의 유사성을 통해 질병과의 연관을 예측하는 방식을 도입했다. 기존에 알려진 질병 유전자와 유사한 특성을 가지는 후보 유전자는 질병과 관련될 가능성이 크다는 것에 기반에 유전자와 질병의 새로운 연관성을 찾아낼 수 있다. 

### 1.2. 목표 및 주요 내용
> &nbsp;본 과제에서는 DisGeNET의 데이터베이스를 통해 질병과 유전자, gda를 수집하고 이를 바탕으로 이기종 그래프를 구성한다. 이후, GCN 기법을 적용해 모델을 생성하여 질병과 유전자의 관계를 학습하고 하이퍼 파라미터의 조정, 최적화 기법 적용 등 모델 고도화를 위해 다양한 노력을 수행해 최적화된 모델을 도출해 내는 것을 목표로 한다.


## 2. 상세설계
### 2.1. 시스템 구성도
![모델 아키텍처](https://github.com/user-attachments/assets/136fc0cb-07f3-45a0-99e3-3a0c53602fd1)

### 2.2. 사용 언어 및 라이브러리
> - Python
> - PyTorch
> - PyTorch-Geometric

## 3. 설치 및 사용 방법
> - 데이터 파일과 ipynb 파일 다운로드 후 Jupyter Notebook 또는 Google Colab에서 실행
> - 모델 세부 구조, 최적화 등의 상세 과정은 보고서 참고

## 4. 소개 및 시연 영상
[![2024전기 졸업과제 7조 동영상](https://img.youtube.com/vi/N4V-dY3biHE?si=jsw21TxUOOT33JLW/0.jpg)](https://www.youtube.com/watch?v=N4V-dY3biHE?si=jsw21TxUOOT33JLW)
<!--[![부산대학교 정보컴퓨터공학부소개](http://img.youtube.com/vi/zh_gQ_lmLqE/0.jpg)](https://www.youtube.com/watch?v=zh_gQ_lmLqE)    -->
<!--Youtube URL: https://www.youtube.com/watch?v={동영상 ID}-->
<!--Youtube Thumbnail URL: http://img.youtube.com/vi/{동영상 ID}/0.jpg-->

## 5. 팀 소개
- 김이경 grindabff@pusan.ac.kr
  - 주요 라이브러리 학습
  - 데이터 전처리
  - 베이스 모델 구축

- 박화성 p2021770@pusan.ac.kr
  - 데이터 전처리
  - 성능 측정 및 모델 최적화
  - 시연 프로그램 구현

- 이윤재 gooneryj1917@pusan.ac.kr
  - 아키텍처 설계
  - 데이터 수집 및 추가 수집
  - 데이터 시각화
