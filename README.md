브라질 이커머스 olist EDA를 통한 효율적인 마케팅 진행
===========

팀원 구성
----------
1. 기간 
2020.02.02 - 2020.02.17

2. 인원
- 2명

3. 역할
- 이지홍 : 데이터 전처리, 데이터 통합, 요일&시간에 따른 주문 분석, 배송&리뷰 분석, 데이터 시각화, PPT
- 최민권 : 데이터 전처리, 데이터 통합, 월&일 매출 분석, 카테고리 분석, 데이터 시각화, PPT

프로젝트 개요
----------
1. 주제 
- 브라질 이커머스 olist EDA
2. 배경
- "11번가 4분기 매출은 증가했으나 마케팅 비용의 증가로 영업이익 감소" 기사를 보고 효율적인 마케팅의 중요성 인지 [기사참조](http://www.ddaily.co.kr/news/article/?no=208937)
3. 목적
- EDA를 바탕으로 효율적인 마케팅 진행(해당 데이터 기준)


데이터 소개
---------
\* 브라질 이커머스 olist
1. 수집 방법 : kaggle [olist](https://www.kaggle.com/olistbr/brazilian-ecommerce)
2. 종류 및 특성(통합데이터 기준)

- 기간 : 2016.10 ~ 2018.08
- 매출액 : $RS 15,218,524 (약 31억 2000만원)
- 회원 수 : 약 95,000명
- 데이터 : 상품 정보, 구매 상태, 판매자 정보, 고객 정보, 배송 정보, 구매자 지역 정보, 지불 방법, 리뷰 정보

분석 과정 
--------

### 1. 데이터 전처리 & 통합
- 총 7개의 데이터를 order_id와 customer_id로 통합 후 결측치 row 처리



### 2. 기간에 따른 분석 

#### 2-1) 월별 / 일별 배출 분석
![스크린샷 2021-05-13 오후 1 30 07](https://user-images.githubusercontent.com/78460413/118077627-710a7b00-b3ef-11eb-9c58-2d786f267698.png)
- 11월의 블랙 프라이데이로 인한 매출급등세를 보임


#### 2-2) 요일과 시간별 구매수 분석
![스크린샷 2021-05-13 오후 1 34 11](https://user-images.githubusercontent.com/78460413/118077999-335a2200-b3f0-11eb-9b30-7429d2ba5fb4.png)
- 평일 소비 집중, 주말 감소 추세를 보이며 월요일 오후 12시 이후 기점 오후 시간대 가장 높은 구매수를 보임



### 3. 카테고리 분석
![스크린샷 2021-05-13 오후 1 46 19](https://user-images.githubusercontent.com/78460413/118078936-1888ad00-b3f2-11eb-9538-6d7da9755e78.png)
- 매출은 11월 블랙 프라이데이 행사 이후 급감세를 보이나 전반적으로 상승세를 보임
- 2018년의 대부분의 카테고리는 정체된 성장과 감소세를 보이나 health beauty, houseweares, telephony 분야 증가세를 보임
- 2018년 경제 회복에 따는 건설업 성장과 더불어 건설 중장비의 수요 증가세를 보임

4. 배송&리뷰 분석

결론 
--------

1. 일요일 저녁부터 평일 오후 1시- 오후 5시까지 구매 수 집중

2. 블랙 프라이데이와 같은 큰 프로모션의 활용

3. Boleto 활용도가 높음

4. 증가하고 있는 카테고리 중 경기의 영향을 덜 받는 health beauty, housewares 에 집중 

5. 평점과 배송 기간의 상관 관계를 보임

6. 평점 상승과 함께 구매 수 증가하는 추세

7. 평점이 낮을수록 고객 응대 시간 단축되는 경향을 보임



Reference
---------
- 권하영 (2021, 02, 03). 11번가 4분기 매출 전년비 15%↑…마케팅비용 증가로 지난해 적자 전환. <디지털데일리>. URL: http://www.ddaily.co.kr/news/article/?no=208937
- 최선욱 (2019). <브라질, 높은 성장을 보이고 있는 전자 상거래 시장>. 상파울루: KOTRA. [KOTRA 보고서1](https://news.kotra.or.kr/user/globalAllBbs/kotranews/album/781/globalBbsDataAllView.do?dataIdx=178787&column=&search=&searchAreaCd=&searchNationCd=&searchTradeCd=&searchStartDate=&searchEndDate=&searchCategoryIdxs=&searchIndustryCateIdx=&searchItemNam)
- 최선욱 (2018). <브라질, 경기 회복과 더불어 건설 중장비 수요 증가>. 상파울루: KOTRA. [KOTRA 보고서2](https://news.kotra.or.kr/user/globalBbs/kotranews/782/globalBbsDataView.do?setIdx=243&dataIdx=171562)
- 최선욱 (2019). <브라질 주방용품(식품 조리 기구) 시장 동향>. 상파울루: KOTRA. [KOTRA 보고서3](https://news.kotra.or.kr/user/globalAllBbs/kotranews/album/2/globalBbsDataAllView.do?dataIdx=177841&searchNationCd=101048)
- 최선욱 (2018). <브라질 생활소비재 산업_미용화장품 산업>. 상파울루: KOTRA. [KOTRA 보고서4](https://news.kotra.or.kr/user/globalBbs/kotranews/784/globalBbsDataView.do?setIdx=403&dataIdx=173141)


