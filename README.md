# 카트라이더 메타분석 (Kartrider Meta Analysis)

### 주제 <br>
v1엔진의 레전드 파츠가 출시되기 전후의 메타분석

### 기획배경 <br>

현재 v1엔진의 레전드카트가 시기에 맞지 않게 나와버려 논란이 되고 있는 상황이다. 
카트라이더의 카트등급은 일반, 레어, 레전드, 유니크등급으로 나뉘어져있다. 
보통 새로운 엔진이 나오면 일반, 레어카트를 충분히 내어 파츠의 공급을 충분히 한
이후에 레전드, 유니크카트의 출시를 시작한다. 하지만 이번에는 그에 맞지 않게
레전드카트를 출시하여 레전드 파츠가 풀림으로써 이에 대한 유저의 부담이 
늘어났다. 과연 이 상황은 현재 메타에 어떤 영향을 주었을까.

### 내부 디렉토리 구조 <br>

```python
Kartrider_Meta_Analysis
┖ .vscode
┖ Crawl			
  ┖ Kartrider_data_1.ipynb # 매치리스트 조회를 통한 매치고유식별자 조회
  ┖ Kartrider_data_2.ipynb # 매치상세정보 조회를 통해서 매치정보와 플레이어정보 조회
  ┖ Kartrider_user.ipynb # 멤버고유 ID 리스트화
┖ EDA # 데이터 전처리
  ┖ Kartrider_eda_1.ipynb
  ┖ Kartrider_eda_2.ipynb
┖ ML # 3가지 Model (RandomForestClassifier, CatBoostClassifier, XGBClassifier) 머신러닝 진행
  ┖ Kartrider_ML_1.ipynb
  ┖ Kartrider_ML_2.ipynb
┖ PPT
  ┖ Project_PPT.pdf
  ┖ Project_script.txt
┖ catboost_info
┖ data
  ┖ kartrider_data.csv # Crawl 이후의 csv
  ┖ kartrider_eda.csv # EDA 이후의 csv
  ┖ pre_error.csv # API 호출 중의 에러 확인
Columns.md # Columns 정보

```

### 세부내용 <br>
https://velog.io/@colacan100/KartriderMetaAnalysisProject-Result

---
