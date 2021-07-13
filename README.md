# Data-Processing-Practice_Titanic
Practicing about Data Processing 
# 데이터 전처리 실습

- 타이타닉 생존자 예측 문제 데이터의 전처리
- Titanic Survival Prediction Problem

<img src="https://raw.githubusercontent.com/data-labs/image/main/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-01-07%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%2010.36.15.png?raw=1" width=400 align='left'><br/>

<br/>
<br/>
<br/>
<br/>
<br/>
  
<br/>
 <br/>
 <br/>
 <br/>
 <br/>
 <br/>
 <br/>
 <br/>
 <br/>
- About the Data<br/>
타이타닉 탑승자 개인별 데이터를 보고 생존 여부를 예측하는 예제 데이터

Survival - 생존여부(타겟변수 y): 0 = No, 1 = Yes

Pclass - 티켓 등급: 1 = 1st, 2 = 2nd, 3 = 3rd

Sex - 성별: male, female

Age - 나이

SibSp - 동승한 형제, 배우자 수

Parch - 부모와 자녀의 수

Ticket - 티켓 번호

Fare - 승선 요금

Cabin - 캐빈(객실) 번호

Embarked - 승선한 항구: C = Cherbourg, Q = Queenstown, S = Southampton
 <br/>
 __________________________________________________________________________________________________________________________________________________
 
 **Why and When do we do Log transformation?** 
 
- It allows us to make a better linear relationship (thus, "explaining" better) between the input (x) and output (y).
- Log transformation input can be the following:
  - Money, Finance-related
  - Biological reaction
  - Sound 

 Example from Real-estate example/부동산:
 지하실 면적처럼 면적이 크다고 면적에 비례해서 집 값이 올라가는 것이 아니라 큰 값을 약화시키는 것이 더 모델의 성능을 개선시키는 사례도 있습니다. 이러한 사례는 경험과 시행착오로 찾는 것입니다. (데이터의 확률 분포를 보고 가능한 정규 분포 모양을 따르는지 보고 관찰합니다.
