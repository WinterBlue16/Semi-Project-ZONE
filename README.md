# Semi-Project-ZONE

> 다음은 이미지분석 AI 서비스 개발 실무과정에서 진행한 Semi-project에 대한 정보이다. 총 다섯 개의 프로젝트를 진행하였으며, 자세한 부분은 이하와 같다. 
<br>
<br>
<br>

## 1. DAUM news comments scarping
![1280px-Daum_communication_logo svg](https://user-images.githubusercontent.com/58945760/73834548-42e2d680-484f-11ea-9922-a3659ff5e5de.png)
> 대형 포털에 연결된 기사들을 크롤링하는 과정에서 1차 댓글만 크롤링하는 것이 아닌, 댓글 아래 달린 답댓글까지 모두 크롤링하여 더 많은 정보를 효과적으로 수집하려 시도하였다. 
<br>
- 웹 크롤링을 통한 기사 댓글+답댓글 수집
- 다음 플랫폼 크롤링 담당
<br>
<br>

## 2. Titanic classification 
![p04zmljn](https://user-images.githubusercontent.com/58945760/73834418-031bef00-484f-11ea-9afe-5c6cb19c014d.jpg)
> 가장 유명한 dataset 중 하나인 타이타닉 승객 dataset을 활용하여 승객들을 생존, 사망으로 분류하였다. 모델링에서 과정 중 배운 다양한 머신러닝 모델을 이용하여 정확도를 비교하였고, 보다 효과적인 모델을 찾으려 시도하였다. 
<br>
- DecisionTree, RandombForest, XGBoost 등 다수의 Mechine Learning Model을 적용하여 성능 비교.<br>
- 모델 적용 및 시각화 담당
<br>
<br>

## 3. Speeddate classification 
![2](https://user-images.githubusercontent.com/58945760/73834686-81789100-484f-11ea-8d0c-c2629a5909ca.jpg)
> kaggle의 speeddate dataset을 활용하여 각 매치들의 성공/실패를 분류하였다.
<br>
- 역시 다수의 Mechine Learning Classifier에 AutoKeras 활용
<br>
<br>

## 4. Carplate detection
![3](https://user-images.githubusercontent.com/58945760/73834633-64dc5900-484f-11ea-99d3-cd6411f40c5a.png)
![1](https://user-images.githubusercontent.com/58945760/73834668-76bdfc00-484f-11ea-8615-73ff1fded9a0.png)
> OpenCV를 활용하여 번호판만으로 전체 자동차를 찾아낼 수 있는 검색기를 만들려 시도하였다. 
<br>
- OpenCV를 활용하여 자동차 번호판의 정보 추출, 번호판 정보만으로 원본 차와 Matching하는 프로그램 제작<br>
- 원본 사진에서 자동차 번호판 슬라이싱, 정보 추출 및 데이터 전처리 담당 
<br>
<br>

## 5. How many days can I be absent?
![not-back-to-school](https://user-images.githubusercontent.com/58945760/74927190-8118f200-541a-11ea-8ef7-2370b2e15234.jpg)
> 면접, 다양한 시험 응시 등으로 수료 시간을 다 채우지 못할까 걱정하는 수강생들의 고민에서 출발해 얼마나 결석할 수 있는지를 상세히 알려주는 웹페이지를 만들었다.

- Django를 활용하여 교육 수료까지 결석할 수 있는 시간을 계산, 수강생 개인별 출석 현황까지 알려주는 웹 페이지 제작
- Codepen, Mobirise, fondawesome 활용
- [화면 계획서]() 작성과 교육생 출석 데이터셋 만들기, 출석 현황 결과 페이지 디자인 담당

- 홈페이지 메인 화면
![홈페이지 화면](https://user-images.githubusercontent.com/58945760/74927814-ad813e00-541b-11ea-8734-c35cdc796cdc.png)



- 이름 입력 부분
![캡처](https://user-images.githubusercontent.com/58945760/74927816-aeb26b00-541b-11ea-84d5-b3b4d07fefbc.PNG)

- 결과 페이지
> 출석률 

![출석 웹페이지](https://user-images.githubusercontent.com/58945760/89731864-83810e00-da85-11ea-9740-9aeefbea53e9.PNG)
![김충희 출석시간](https://user-images.githubusercontent.com/58945760/89731875-98f63800-da85-11ea-97f6-73276179f8d8.PNG)

> 결석가능일수 & 결석가능시간

![결석가능시간](https://user-images.githubusercontent.com/58945760/89731889-b6c39d00-da85-11ea-8e12-8771955ecbb3.PNG)

> 요일별 출석률

![일별 출석율](https://user-images.githubusercontent.com/58945760/89731899-cc38c700-da85-11ea-8186-9267eac8ef05.PNG)

