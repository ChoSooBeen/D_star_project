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
> > > colab - D_star4.ipynb ~~(용량이 커서 안올라감, 후에 정리해서 올림)(https://colab.research.google.com/drive/1oO8z-dUynOiMFDGgoVsNvfnWUYBPzDfR#scrollTo=qMvBn4uWntF8)~~          https://github.com/ChoSooBeen/D_star_project/blob/main/D_star4.ipynb   **<2022.09.19 각 클래스별 100장 이상씩 증강완료>**
> > 4. dataset 만들기
> > > 2022.09.20 레이블별 파일 생성 완료 : 데이터가 너무 많아서 구글 드라이브와 업로드 시간차가 큼    
> > > 2022.09.22 클래스별 이미지 분류 
