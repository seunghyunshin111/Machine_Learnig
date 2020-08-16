# ML/DL Model



- Modeling 이 끝나면 나오는 것이 "Model"

- Model: 파라미터들의 집합

- 모델을 wx + b로 본다면 우리가 알고 싶은 것은 w, b이다. w, b의 집합이 모델임

- 학습된 파라미터 = 모델링 

- 무엇을 학습을 하는가?  과거에 주어진 데이터들을 가지고 새로운 결과를 위해 학습시키는 것

- 과거의 데이터들이 가지고 있는 특징을 기반으로 새로운  인사이트를 잘 도출하기 위해 학습하는 것

- 학습된 파라미터는 과거의 데이터를 포함하고 있다.

  <br>

- 최신 트렌드: Modeling(학습)하지 말자.

  Ex. ImageNet에 1,000개의 Object가 있고, 여기엔 이미 학습된 데이터가 있다. 여기 이미 학습된  것을 활용해서 쓰자. => "Transfer Learning"

  

- **Transfer Learning** 

  - 결과가 잘 나온다.

  - ### Teachable machine

    - "Fine Tuning"
    - Image(CNN), Audio(LSTM), Pose(LSTM)
    
    

- 구글 목표: 우리가 이런 것들은 만들어 줄 테니, 이 모델을 활용해 사람들이 서비스 형태로 산출하라는 것



- ### Parameters Learned -> Transfer Learning -> Fine Tuning -> Service Export



- 우리가 직접 ML/DL Model 할 필요 X
- 대부분 DL은 오픈소스로 공개된다.