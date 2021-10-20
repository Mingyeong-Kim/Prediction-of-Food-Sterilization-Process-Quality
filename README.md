# Prediction-of-Food-Sterilization-Process-Quality

- **프로젝트 기간: 2021.06.04 ~ 2021.06.21(2주, 개인)**
- **프로젝트 개요: 의사결정 나무 모델을 활용하여 식품 살균 공정에서 양품이 생산되는 온도 범위 예측하기**
- **사용기술: Python(Google Colab), Tensorflow**
- **사용모델: 의사결정나무모델(Decision Tree)**

## 프로젝트 목표
- 일관적이고 정확한 공정제어를 위해 머신러닝 모델을 활용하여 식품 살균 공정에서의 양품이 생산되는 온도   
  범위를 예측하고자 했습니다.

## 프로젝트 과정 및 내용

1. 데이터셋 준비
   - 식품살균공정의 각 공정라인별, 제품별 살균온도에 따른 불량품 여부 데이터(KAMP 제조AI데이터셋)
 
2. 탐색적 자료 분석(EDA)
   - 기술통계, 상관계수 분석

3. 데이터 전처리
   - 결측치 제거

4. 데이터 모델링
   - 의사결정나무모델

5. 모델 평가 및 결과분석
   - 모델 평가 지표
     - 정확도(Accuracy)
     - 정밀도(Precision)
     - 재현율(Recall)
     - F1-Score

## 프로젝트 결과
- **모델 결과**
- <img width="600"  height="400" src="https://user-images.githubusercontent.com/65681568/138156365-dc19ade6-1ea4-470a-bc90-64e855398641.png">
- 살균공정에서 살균기B의 살균온도는 61.95℃ 이상, 살균기A의 살균온도는 57.95℃ 이하로 운영하는 경우에 양품을 생산할 수 있다고 예측하였다.
 
- **모델 평가**
  - **정확도(Accuracy):** 0.9185
  - **정밀도(Precision):** 0.9294
  - **재현율(Recall):** 0.9788
  - **F1-Score:** 0.9535

- **고찰**
  - 의사결정나무모델을 사용해서 만든 AI모델을 사용하여 살균 공정에서 제품에 따라 온도조절을 하지 않아 발 
   생하는 불량률을 줄일 수 있을 것이다.
  - 추가 데이터를 활용한 검증이 필요할 것으로 보인다.


