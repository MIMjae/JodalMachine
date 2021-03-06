## 공공조달 빅데이터 경진대회 | 데이터 분석 분야

### :star: 조달청 나라장터 종합쇼핑몰 추천시스템 개발 :star:
- 팀명 : 조달머신
- 팀원 : 김민석, 박민재, 전형준, 정재훈
- 기간 : 2022.01.05 ~ 2022.04.08


### 01. 활용 모델
- 아이템 기반 협업 필터링
- 잠재요인 기반 협업 필터링

### 02. 활용 데이터
- 조달정보개방포털
  - 종합쇼핑몰 품목 등록 내역
  - 종합쇼핑몰 납품요구 상세내역

### 03. 요약

(1) 배경
- 시대에 맞는 혁신 기술을 활용해 사용자의 불편함과 기업 간 불균형을 해소하기 위해 나라장터 종합쇼핑몰 추천시스템을 개발한다.
- 정부와 조달청의 의무구매제도와 우선구매제도를 평점에 반영하여 사용자의 편의를 높이는 시스템을 구축한다.
  - 의무구매제도 : 공공기관의 녹색 제품의 ˿매를 의무화하는 제도저공해자동차인증, 저탄소인증제품
  - 우선구매제도 : 조달청의 우수제품으로 지정된 제품이나 희망기업의 제품 등을 우선으로 구매하도록 하는 제도

(2) **평점 데이터셋 정의**
- 평점 = 사용자의 구매 횟수 + 가산점
- 가산점 : 의무구매제품 => 10점, 우선구매제품 => 1점

(3) 모델링
- 평가 : MSE, RMSE

### 04. 기타
- 협업 도구 : Notion, Google Colab
- 활용 언어 : Python
- 분석 도구 : JupyterNotebook, Excel
        

