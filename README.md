# Activity-Classification-Challenge

연세대학교 대학원 수업 Machine Learning and Pattern Reognition 에서 진행된 프로젝트 Challenge 

6가지 Activity 분류

- Class 1: Walking
- Class 2: Walking upstairs
- Class 3: Walking downstairs
- Class 4: Sitting
- Class 5: Standing
- Class 6: Laying

스마트폰의 가속도계와 자이로스코프로 측정된 데이터로 진행

* Train Data 
  - 총 6969개 
  - 데이터 1개 당 128X6 매트릭스 포함 : 6개 정보(Accelerations X, Y, Z 방향 + angular velocities X, Y, Z 방향)의 128 Samples
  - Activity에 대한 라벨링 되어 있음
  
* Test Data : 총 2947개
  - 데이터 1개 당 128X6 매트릭스 포함 : 6개 정보(Accelerations X, Y, Z 방향 + angular velocities X, Y, Z 방향)의 128 Samples
  - 라벨링 X

* Schedule
  - 2020.6.1 : 프로젝트 시작
  - 2020.6.18 23시59분 : 제출 데드라인

* 활용 모델 : Convolutional Neural Networks

* 결과: 9등 (약 40명 수강생 중, 기준: 정확도) 

