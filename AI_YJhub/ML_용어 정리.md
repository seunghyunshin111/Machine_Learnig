# ML 용어 정리

**면접 질문**

- Lenear Regression, 로지스틱, 소프트 맥스 Regression 차이
- Gradient Descent, Normal Requ.. 과의 차이점, 어떤 경우에 사용해야 하는데
- 정규화 기법. Regularization, Lidge, Lasso 의 의미가 각각 무엇이고, 각각을 언제 쓰면 좋을 지의 차이점에 대한 질문
- Regression: 인간이 개입하는 것이 많다. 함수를 보고 직접 1차 함수, 지수함수로 할지 하고, 리그레션은 파라미터를 정해주는 것 / 딥러닝은 그 선택조차도 하지 않는다.

<br>

## Regression

- Test data, Train data를 설명하시오.

  목적이 다르다.

- Train data: w0, w1의 값을 얻고 싶은 것. 어떤 모양의 직선을 가질 지 정할 수 있음

  문제집, 모의고사(답안도 있음)

- test data: y값 예측, 파라미터가 잘 학습 되었는지, 좋은 output을 얻었는지 확인

  시험(output 변수 삭제)

<br>

- 로지, 소프트 둘 다 분류이지만 로지는 0, 1 두 개이고, 소프트맥스는 아웃풋이 여러 개
- 리니어는 아웃풋이 시험 점수. continuous value (연속형 변수)

---

- X(n, m) 

  m: 피쳐의 개수

---

- 잔차는 음수, 양수가 모두 될 수 있기 때문에, 절대값을 씌워 잔차의 합을 구해야 한다.

- MSE: M: mean, E: error, S: Squared

  E[error**2]: [error제곱]의 평균

- MAE: https://chukycheese.github.io/translation/statistics/absolute-error-and-mean-absolute-error/

- 언제 MSE, MAE를 쓰는 것이 좋은지?
- Large error의 경우 MSE 사용 (제곱을 쓰기 때문에, 값이 커짐. 에러에 페널티를 주고 싶을 때 유용)
- 