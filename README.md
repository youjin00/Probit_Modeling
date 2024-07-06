# Long-term and Short-term Interest Rate Inversion and Economic Forecasting
# 장단기 금리 역전과 경기 예측

---


## Project Overview
This project involves empirical analysis using Probit and GARCH models to predict economic recessions based on the inversion of long-term and short-term interest rates. The study analyzes economic data from the United States and South Korea to validate different predictive models.

이 프로젝트는 장단기 금리 역전을 기반으로 경기 침체를 예측하기 위해 Probit 모델과 GARCH 모델을 사용한 실증 분석을 포함하며, 미국과 한국의 경제 데이터를 분석하여 다양한 예측 모델을 검증합니다.


---


## Introduction
The project focuses on the predictive power of the inversion of long-term and short-term interest rates in forecasting economic recessions using advanced statistical models.

이 프로젝트는 고급 통계 모델을 사용하여 경기 침체를 예측하는 데 있어 장단기 금리 역전의 예측력을 중심으로 합니다.


---


## Models Used
1. **Model A**: Uses the spread between 10-year and 3-month Treasury rates.
2. **Model B**: Adds the nominal Federal Funds Rate to Model A.
3. **Model C**: Adds the real Federal Funds Rate to Model B.
4. **Model D**: Adds the yield forecasting coefficient to Model B.

---

1. **모델 A**: 10년과 3개월 만기 국채의 금리 스프레드를 사용합니다.
2. **모델 B**: 모델 A에 명목 연방기금금리를 추가합니다.
3. **모델 C**: 모델 B에 실질 연방기금금리를 추가합니다.
4. **모델 D**: 모델 B에 수익률 예측 계수를 추가합니다.




## Analysis
### United States
- **Model A**: The term spread is not statistically significant in predicting recessions.
- **Model B**: Both the term spread and nominal Federal Funds Rate are significant predictors.
- **Model C**: Adds the real Federal Funds Rate, which also shows statistical significance.
- **Model D**: The inclusion of the yield forecasting coefficient further improves the model’s predictive power.

### 미국
- **모델 A**: 기간 스프레드는 경기 침체 예측에 통계적으로 유의미하지 않습니다.
- **모델 B**: 기간 스프레드와 명목 연방기금금리는 유의미한 예측 변수입니다.
- **모델 C**: 실질 연방기금금리를 추가하여 통계적으로 유의미한 결과를 보입니다.
- **모델 D**: 수익률 예측 계수를 추가하여 모델의 예측력을 더욱 향상시킵니다.

### South Korea
- Similar models were applied with adjustments for local economic indicators.
- **Model D** was found to be the most effective in both in-sample and out-of-sample evaluations.

### 한국
- 지역 경제 지표에 맞춘 조정을 통해 유사한 모델을 적용했습니다.
- **모델 D**가 내표본 및 외표본 평가에서 가장 효과적인 것으로 나타났습니다.


---

## Results
- **Model D** consistently showed the highest predictive accuracy across different datasets.
- BIC and McFadden’s R-squared metrics indicated Model D's superior fit and explanatory power.
- ROC curves and AUC values confirmed Model D's excellent classification performance.

- **모델 D**는 다양한 데이터셋에서 지속적으로 가장 높은 예측 정확도를 보였습니다.
- BIC와 McFadden의 R-squared 지표는 모델 D의 뛰어난 적합성과 설명력을 나타냈습니다.
- ROC 곡선과 AUC 값은 모델 D의 우수한 분류 성능을 확인했습니다.

---


## Conclusion
Model D, incorporating the yield forecasting coefficient, proved to be the most effective in predicting economic recessions. Differences in model performance between the US and South Korea suggest the need for region-specific adjustments and considerations.

수익률 예측 계수를 포함한 모델 D는 경기 침체 예측에 가장 효과적인 것으로 입증되었습니다. 미국과 한국의 모델 성능 차이는 지역별 조정과 고려가 필요함을 시사합니다.



---



## Contribution
To contribute, please open an issue or submit a pull request.

기여를 원하시면 이슈를 등록하거나 PR을 제출해 주세요


---

## License
This project is licensed under the MIT License.

이 프로젝트는 MIT 라이선스를 따릅니다.
