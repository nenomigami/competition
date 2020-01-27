### 기록



- 1 Adversarial: auc 0.62, KS reject 열삭제, 추가로 열 삭제 10개

   ,  NA처리 -99999 , 문자열 처리 -999 

  Catboost (seed = 10) :  1.6668371341116557 / public 1.98015

  

- 2 Adversarial: 0.58, KS reject 열삭제, 추가로 열 삭제 20개

   NA처리 -99999 , 문자열 처리 -999 

  Catboost (seed = 10) :  2.1215928063465253 / 



- 3 Adversarial: 0.55,  drifted variable 1740개 삭제(catboost)

  ,  NA처리 -99999 , 문자열 처리 -999 

  Catboost (seed = 10) :  

  train : 0.6475742	

  valid : 1.1088158

  test: 2.69003

  

- 4 Adversarial: 0.65, KS reject 열만 삭제,  NA처리 -99999 , 문자열 처리 -999 

  Catboost (seed = 10) :  

  train : 1.1236745	

  valid : 1.7139294 / 1.5630262

  test:   1.74828

  

- 5 Adversarial: , KS reject 열 삭제 + feature importance 500개 투입

  ,  NA처리 -99999 , 문자열 처리 -999 

  Catboost (seed = 10) :  

  train : 

  valid : 

  test:   

- 6 Adversarial: 1.0 ,  NA처리 -99999 , 문자열 처리 -999 (전체 데이터 셋)

  Catboost (seed = 10) :  

  train :

  valid : 

  test:  





- Adversarial: 0.62, KS reject 열삭제,  NA처리 -99999 , 문자열 처리 -999 

  StandardScaler 2.42655

  Catboost(seed = 10): 

- Adversarial: 0.62, KS reject 열삭제,  NA처리 -99999 , 문자열 처리 -999 

  StandardScaler PCA

  Catboost(seed = 10): 

- Adversarial: 0.62, KS reject 열삭제,  NA처리 -99999 , 문자열 처리 -999 

  StandardScaler variance treshold 

  Catboost(seed = 10): 

- Adversarial: 0.62, KS reject 열삭제,  NA처리 -99999 , 문자열 처리 -999 

  StandardScaler variance treshold except categorical_value 

  Catboost(seed = 10): 