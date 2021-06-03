### 빅데이터 처리 
##### 32152332 송인호
<br>
* Data_preprocessing1.ipynb
    - 1개의 (origin)을 (preprocessed)로 바꾸는 노트북
    - 결과적으로 (업종, 시, 사업자 수) 의 Column을 가진 1818개(18*101) Row 파일 생성 
    - origin        : "YYYY_MM.csv" 
    - preprocessed  : "YYYY_MM_total.csv"

* Data_preprocessing1-M45.ipynb
    - 4월, 5월(origin) 파일을 따로 (preprocessed)로 바꾸는 노트북
    - 4월, 5월의 경우, 다른 파일들과 형식이 조금 달라서 자동화가 어려워 수작업으로 전처리하였음
    - 결과적으로 (업종, 시, 사업자 수) 의 Column을 가진 1818개(18*101) Row 파일x2개 생성 
    - origin        : "YYYY_MM.csv" 
    - preprocessed  : "YYYY_MM_total.csv"

* Data_preprocessing_Auto.ipynb
    - Data_preprocessing1.ipynb의 자동화 버전
    - 약 22개의 (origin)을 22개의 (preprocessed)로 바꾸는 노트북
    - 인코딩문제로 원활히 작동하지 않을 수 있는데, 이때 그저 인코딩을 바꿔주면 해결됨
    - 결과적으로 (업종, 시, 사업자 수) 의 Column을 가진 1818개(18*101) Row 파일x22개 생성 
    - 20년 4,5월을 제외한 (19년 2월 ~ 20년 12월)의 (preprocessed) 파일들을 생성
    - origin        : "YYYY_MM.csv" 
    - preprocessed : "YYYY_MM_total.csv"