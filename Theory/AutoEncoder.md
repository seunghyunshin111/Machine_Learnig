## AutoEncoder

- 비지도 학습(Unsupervised learning)

![image-20201007150632787](C:\Users\sundo\AppData\Roaming\Typora\typora-user-images\image-20201007150632787.png)

- 가운데의 Hidden layer의 뉴런 수를 Input layer보다 작게 해서

  데이터를 압축(차원을 축소)한다거나

- 입력 데이터에 Noise를 추가한 후

  원본 입력을 복원할 수 있도록 네트워크를 학습시킨다.

<br>

- 인코더(Encoder): 인지 네트워크(recognition network)라고도 하며, 입력을 내부 표현으로 변환
- 디코더(Decoder): 생성 네트워크(generative network)라고도 하며, 내부 표현을 출력으로 변환한다.



- 오토인코더는 입력과 출력층의 뉴런 수가 동일하다.
- 입력을 재구성하기 때문에 '출력을 재구성'이라고도 한다. 



![image-20201007151454517](C:\Users\sundo\AppData\Roaming\Typora\typora-user-images\image-20201007151454517.png)





- 오토인코더에서 PCA를 수행할 수 있다.





https://excelsior-cjh.tistory.com/187 추가학습

