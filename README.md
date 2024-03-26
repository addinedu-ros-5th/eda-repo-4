# <img src = "https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/f905a6e2-c402-4258-87bd-a84215d9b586" width="37" height="37"> 스킨케어 제품 분석 <img src = "https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/f905a6e2-c402-4258-87bd-a84215d9b586" width="37" height="37">

![스크린샷 2024-03-26 오전 11 42 28](https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/8f9b11df-8d88-40db-8536-563e86fa02c1)


# 1. 👨‍🏫 프로젝트 소게 👨‍🏫
## 1.1 프로젝트 목표 🎯 
- 웹 페이지 정보 크롤링 기술을 실습하고, 수집된 데이터 간의 연관성을 분석하여 데이터 상관 관계 분석 역량을 강화
- API와 GUI 모듈을 활용하여 분석 결과를 기반으로 한 사용자 친화적인 서비스 제공
- 과정을 통해, 데이터 분석의 흐름 파악 및 분석된 데이터를 바탕으로 한 서비스 제공을 통해 데이터 활용능력 향상

## 1.2 프로젝트 진행과정 🏃🏻 
<img width="842" alt="스크린샷 2024-03-26 오후 1 58 05" src="https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/5a7137ad-0676-4b31-af92-921c810e8b9d">

## 1.3 팀구성  
- 이민영(팀장) :
- 곽민기 :
- 김준영 :
- 홍권호 : 성분 데이터 크롤링, 성분에 따른 특징 분석 

## 1.4 프로젝트 기술 💻
![스크린샷 2024-03-26 오후 2 01 35](https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/2f8a78dd-3614-4060-8a2d-b666cb31bd48)

# 2. 👨🏻‍💻 데이터 수집 👨🏻‍💻
## 2.1 데이터 정보 ℹ️
- 올리브영 스킨케어 제품 카테고리의 스킨/토너 , 에센스/세럼/엠플, 크림, 로션 제품들의 브랜드, 원가, 리뷰정보, 성분에 대한 데이터
![스크린샷 2024-03-26 오전 10 49 25](https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/940b3a89-d965-429b-8b79-071fbf433a3a)
![스크린샷 2024-03-26 오전 10 49 42](https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/e59365c4-6b52-40e5-8b0f-229cbd9f6554)


## 2.2 데이터 수집 1차 📌 
- Selenium과 beautifulsoup을 활용해 1차 적으로 제품명, 브랜드, 가격, 리뷰정보를 수집
>( 구체적인 1차 수집 과정과 코드는 [제품 크롤링, 분석] 레파지토리에서 확인 가능합니다 )

<img width="1125" height="350" alt="스크린샷 2024-03-26 오전 10 51 21" src="https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/7b0de00b-fb68-4c08-a508-d1e064559778">

- 1차 데이터를 수집한 후, 성분 분석에 대한 의견이 제시되었습니다. 그래서 추가적으로 성분 정보를 포함한 전체 데이터를 수집하게 되었습니다

## 2.3 데이터 수집 2차 📌
- 제품의 성분을 포함한 전체 데이터를 수집
>( 구체적인 2차 수집 과정과 코드는 [성분 크롤링, 분석] 레파지토리에서 확인 가능합니다 )
![스크린샷 2024-03-26 오전 10 59 50](https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/161a48e7-4df7-47b3-9f65-aa097a191cd6)
![스크린샷 2024-03-26 오전 10 59 56](https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/229dbecd-d217-42c8-af4c-18b1becdb843)

## 2.4 수집한 데이터를 데이터 베이스에 저장 ✓
<img width="961" alt="스크린샷 2024-03-26 오전 11 11 36" src="https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/82f4bdc9-67eb-4ac8-8faf-81c1503f8de4">

# 3. 📊데이터 분석 및 시각화📊
## 3.1 제품의 가격, 브랜드, 평점, 리뷰정보 데이터를 분석해 브랜드별 제품의 특징을 분석 🧐

## 3.2 같은 리뷰 특징을 갖는 제품들 사이 성분에 따른 가격, 평점 분석 🧐
>( 리뷰 내용과 가격에 따른 제품을 찾고 제품사이 겹치는 성분을 도출하는 구체적인 함수는 [성분 크롤링, 분석] 레파지토리에서 data_analysis.ipybn 파일에서 확인가능합니다)
<img width="400" height="350" alt="스크린샷 2024-03-26 오후 5 17 04" src="https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/87c70166-2930-439a-a215-21440d93feca">
<img width="400" height="350" alt="스크린샷 2024-03-26 오후 5 17 25" src="https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/b66115a0-34be-4c22-87b5-a9fd8f42e661">
<img width="950" alt="스크린샷 2024-03-26 오후 5 17 33" src="https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/38072578-e8c6-40fb-86ab-ba8d0f1479ee">
<img width="950" alt="스크린샷 2024-03-26 오후 5 37 14" src="https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/1fe47b72-8bd6-437b-a369-ba8cd4edd875">


- 해당 자료만으로는 특정 성분이 해당 리뷰 평가와 가격등에 요소에 영향을 미치는지 단정 짖기 어려워 가격을 제외하고 리뷰평가 별로 만 비교해 봄

<img width="400" height="350" alt="스크린샷 2024-03-26 오후 5 24 20" src="https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/3266ddac-fa8e-4f30-af81-9e1ef324db33">
<img width="400" height="350" alt="스크린샷 2024-03-26 오후 5 24 28" src="https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/167227df-125e-418c-a07c-0848fb4cd965">
<img width="950" alt="스크린샷 2024-03-26 오후 5 24 59" src="https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/01a24fa8-c723-4a76-b65a-3daa80c44140">
<img width="950" alt="스크린샷 2024-03-26 오후 5 39 45" src="https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/6cc0f90a-8a46-472b-947f-d4bf525c46ee">

- 리뷰평이 높으면서 가격이 높은 제품들에 글리세린, 부틸렌글라이콜,에틸핵글리세린 등의 성분 빈도가 높은 모습을 볼 수 있다.
- 하지만 성분의 종류가 많고 해당 빈도수가 높게 나온 성분들이 실제로 화장품의 기능과 관련이 있는지 정확하지 않기 때문에 
- 정확한 성분 분석을 위해 '글로우픽' 웹페이지에서 제품을 검색해 제품의 성분의 위험도와 기능등에 대한 정보를 크롤링 해봄





## 3.? 분석결과 🧐

# 4. 📺 분석한 데이터를 바탕으로 한 GUI 서비스 📺
- 원하는 스킨케어 제품 항목을 선택하고 제품의 세부 내용을 결정시 조건에 맞는 제품을 추천
![스크린샷 2024-03-26 오전 11 23 16](https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/fe564fb2-fab4-4fd0-99d0-a0164ac07da7)
   


