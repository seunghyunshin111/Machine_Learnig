# Machine Learning

> t. 이정구

- ## Machine?

  - Machine Learning의 Machine은 **함수**

  - **Function**

  - **Algorithm**

  - **Model**

    <br>

- ## Learning?

  - 궁극적인 목표: 변화를 일으켜야 하는 것
  - 컴퓨터가 학습 목표가 아님
  - '학습'은 전과 후가 바뀌어야 한다.
  - **Change**: 변화는 좋을 수도 나쁠 수도 있다. 경영에서는 **Risk**로 본다.
  - Positive / Negative

  <br>

- ## Machine Learning?

  - **Regression** 예측

    ```python
    y = wx + b (회귀)
    
    # x: Input
    # y: Output
    # w, b: 변경의 주체
    ```

    

  - **Classification** 분류

  <br>

- ## Data?

  - 과거 행동의 결과

<br>

- ## Loss function?

  - 손실값 최소화

<br>

- ## Cost?

  - 여러개의 Loss를 합친 것

<br>

- 우리가 원하는 b를 찾는 것은 '경사하강법'으로 찾는다.
- 경사하강법: 자동으로 찾아준다.
- W, b는 우리 데이터를 설명하는 것
- 함수를 가정하는 데에 Domain knowledge가 중요

<br>

- ## Machine Learning?

  - 데이터를 설명할 수 있는 함수를 찾는 것

  - 최적의 함수를 찾아 최적해를 찾는 것

  - 단일선형회귀 (선)를 사용. 

  - X가 제곱이면 곡선

  - 다중회귀
  
    ```python
    y = a1x1 + a2x2 + b
    
    # 면이 안에 들어가면 좋은 함수
    # x가 제곱이 되면 면이 굽게 된다.
    ```

<br>