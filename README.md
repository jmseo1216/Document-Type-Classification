# Document Type Classification

## 1. 개요
- 다양한 산업에서 문서 이미지는 산업 전반에 가장 많은 데이터로써 대량의 문서 이미지를 식별하고 자동화 처리가 필요.
- 실 데이터 기반 문서 타입을 인식하고 분류하는 이미지 분류 모델을 구축
- 이를 통해 금융, 의료, 보험 등에서의 업무 효율성과 데이터 관리의 신뢰성을 높이기 위함.

## 2. 기술 스택
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=black">
<img src="https://img.shields.io/badge/Pytorch-EE4C2C?style=for-the-badge&logo=Pytorch&logoColor=white">
<img src="https://img.shields.io/badge/Opencv-5C3EE8?style=for-the-badge&logo=Opencv&logoColor=purple">

## 3. Dataset Overview
* train : 1570장의 이미지
* train.csv : 1570개의 행. train 폴더에 존재하는 1570개의 이미지에 대한 정답 클래스 제공
  * ID: 학습 샘플의 파일명
  * target: 학습 샘플의 정답 클래스 번호
* meta: 17개의 행
  * target 17개의 클래스 번호에 대응하는 클래스 이름
* test
  * 3140장의 이미지
* sample_submission.csv : 3140개의 행
  * ID 평가 샘플의 파일명
  * target 예측 결과가 입력될 컬럼 (기존에는 전부 0)
![image](https://github.com/user-attachments/assets/723b5822-4aab-4361-9e3b-ac0f33a965b8)

##  4. Sample Data Augmentation
![image](https://github.com/user-attachments/assets/ee307a92-0818-443d-8997-06f66e2c6fdd)

## 5. Modeling
![image](https://github.com/user-attachments/assets/3a4b6ed3-e438-42fb-9e6c-261a0b790976)