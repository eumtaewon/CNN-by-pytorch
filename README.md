# CNN-by-pytorch
현재 모델 소개:LeNet-5
======================
Yann LeCun 연구팀이 1998년 발표한 CNN알고리즘

활용 데이터: CIFAR10
====================
내용:10가지 범주를 가진 32x32픽셀의 컬러 이미지 데이터 셋

범주:비행기,자동차,새,고양이,사슴,개,개구리,말,배,트럭

Train set=50000개

Test set=10000개

Chapter
========
1.Import Library

2.Data Download

3.Build Model

4.Model Training

5.Prediction Test data set


1.Import Library
=================
분석에 필요한 라이브러리 Import
![image](https://user-images.githubusercontent.com/104436260/176813424-274dd8fa-9062-4644-8bc7-7d3b2b587308.png)

Seed고정

![image](https://user-images.githubusercontent.com/104436260/176813749-c71c3c24-67f8-4006-b073-87def2ed11d0.png)

2.Data Download
================
transforms.Compose() 활용하여 모듈을 생성하여 후에 이미지 데이터를 불러올 때, 한번에 텐서로 변환 및 정규화 시켜줌
![image](https://user-images.githubusercontent.com/104436260/176813942-29e66e42-84d7-43a5-b737-893ef70bc186.png)


torchivision에서 데이터 셋 가져오기

![image](https://user-images.githubusercontent.com/104436260/176814033-ec1a8396-0327-4c86-b87f-0cafea7f69dc.png)
torchvision.datasets.CIFAR10(root=‘데이터저장위치’, train=True # True=train, False=test,download-True #다운로드 여부,transform=transform  #앞장에 데이터 선처리 작업)

torchvision.dataset.CIFAR10->CIFAR10 데이터 가져오기






  
  
