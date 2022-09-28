# D_star_project

> ### 1. 프로젝트 주제
>	>   스마트폰 등을 이용하여 종자 이미지를 촬영하면 그로부터 종류를 자동으로 분류해주는 인공지능

> ### 2. 문제 상세
> > 촬영된 종자 이미지를 입력받아, 테스트셋에서 같은 종의 이미지를 모두 찾아내는 것               
모델은 입력된 이미지가 속할 가능성이 높은 상위 항목을 확률 또는 그에 준하는 지표 정보와 함께 3~5개 사이로 추천

> ### 3. 프로젝트 진행
> > 1. 주어진 데이터 분석하기   
> > > 1.1 제공된 데이터 유형 분석 및 모델 찾아보기(https://github.com/ChoSooBeen/D_star_project/blob/main/%ED%95%9C%EA%B5%AD%EC%88%98%EB%AA%A9%EC%9B%90%EC%A0%95%EC%9B%90%EA%B4%80%EB%A6%AC%EC%9B%90_data_%EB%B6%84%EC%84%9D.docx)        
> > > 1.2 데이터 현황 파악하기: class 당 이미지 수 맞추기! (https://github.com/ChoSooBeen/D_star_project/blob/main/train_label(%ED%98%84%ED%99%A9%ED%8C%8C%EC%95%85).xlsx)
> > 2. 멘토링 참가하기
> > > 2.1 1차 멘토링(https://github.com/ChoSooBeen/D_star_project/tree/main/first_mentoring)     
> > > 2.2 2차 멘토링
> > 3. 데이터 증강시키기    
> > > colab - D_star4.ipynb ~~(용량이 커서 안올라감, 후에 정리해서 올림)~~        
> > > + **<2022.09.19 각 클래스별 100장 이상씩 증강완료>** (https://github.com/ChoSooBeen/D_star_project/blob/main/D_star4.ipynb)   
> > 4. dataset 만들기    
> > > + **2022.09.20 레이블별 파일 생성 완료** : 데이터가 너무 많아서 구글 드라이브와 업로드 시간차가 큼    
> > > + **2022.09.21 클래스별 이미지 분류** (https://github.com/ChoSooBeen/D_star_project/blob/main/D_star_5.ipynb) 
> > 5. 모델 구현
> > > + 2022.09.22 ~~1차 ResNet50 모델 구현 (실패) https://sun-daughter-837.notion.site/1-ab6415fc6f7d4207b026b0177c258b1c~~     
> > > + **2022.09.23 2차 모델 구현(keras.resnet50 라이브러리)**   https://github.com/ChoSooBeen/D_star_project/blob/main/D_star8.ipynb    
> > >   + class 이름을 한글이 아닌 숫자로 변경   (https://github.com/ChoSooBeen/D_star_project/blob/main/D_star9.ipynb)    
> > > + 2022.09.26 ~~3차 모델 구현(2차모델 보완 --> 실패) https://github.com/ChoSooBeen/D_star_project/blob/main/D_star10.ipynb~~
> > > + **2022.09.27 4차 모델 구현(CNN 사용해보았다.)** --> 학습은 된거 같고 정확도도 나쁘지 않은 것 같은데 이것을 어떻게 원하는 결과를 보여줄 수 있도록 하는지 고민할 필요가 있다.   (https://github.com/ChoSooBeen/D_star_project/blob/main/D_star12.ipynb)   
> > > + **2022.09.28 5차 모델 구현(CNN 사용 및 사전학습 모델 사용)** --> 어느정도 코드에 대한 이해를 했고 모델도 90%정도의 정확도를 보였다. 이를 응용해서 원하는 결과 형식으로 나오도록 바꿔야한다. (https://github.com/ChoSooBeen/D_star_project/blob/main/D_star13.ipynb)
> > 6. [notion 프로젝트 정리](https://sun-daughter-837.notion.site/432109fa7df94a50b01af80e31f28b8a)
