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
- 홍권호 :

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


## 3.? 분석결과 🧐

# 4. 📺 분석한 데이터를 바탕으로 한 GUI 서비스 📺
- 원하는 스킨케어 제품 항목을 선택하고 제품의 세부 내용을 결정시 조건에 맞는 제품을 추천
![스크린샷 2024-03-26 오전 11 23 16](https://github.com/addinedu-ros-5th/eda-repo-4/assets/163790408/fe564fb2-fab4-4fd0-99d0-a0164ac07da7)
   


