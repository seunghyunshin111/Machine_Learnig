### 추천 시스템

> 추천 책: Machine Learning at work (첫번째 라이브러리 추천 책)
>
> IT의 모든 역사

### Machine Learning Parameters

> w, b는 데이터를 표현한다.

<br>

# Big Data?

- 크기나 다양성 측면에서 볼 수 있는데, 크기는 상대적, 절대적으로 볼 수 있고, 다양성에는 정형과 비정형으로 되어 있다. 속도는 생성은 빠른 반면 의미는 적어진다. 빅데이터는 상대적으로 볼 수 있기 때문에 한마디로 정의하기는 어렵다.

<br>

##  Big?

- **Volume(크기)**

  데이터가 크다.

  '크기'는 상대적(Computing) (기준이 다 다르다.)

  -  **상대적(Computing)**

    CPU, Memort, Disk, Network, etc...

  -  **절대적**

    ```
    32bit = 2^32만큼 Adress 갖는다.
            2^32 = 2^10 x 2^10 x 2^2
    64bit = 2^64 = 2^10 x 2^10 x 2^10 x 2^10 x 2^10 x 2^10 x 2^4
                    KB     MB     GB     TB     PB     EB  
                                                       *ZB, YB
    ```

    <br>

- **Variety(다양성)**

  - **정형(Structure)**

    'R'의 Data Structure: 벡터(데이터 핸들링 하는 최소 단위) -> 데이터 프레임

    정형화된 데이터를 다루고 얘기하기 위해 만든 것 **SQL**

    **Database**는 정형을 다루기 위해 만들어짐

    RDB: Relation 관계는 즉 **'Table Structure'**

    Table이 중첩되어 있는 것, **DB**

    Table 간의 관계인 **Cell**에는 **Size, Type**이 정해진 data가 들어갈 수 있다.

  - **비정형(Unstructure)**

    이미지/영상이 많다. (야구 하이라이트 장면도 AI가 뽑는다.)

    음성

    비정형 Text(신문기사, 후기 etc) (신문기사 AI 요약 정보도 베타서비스로 제공중)

    **NoSQL**: 비정형 데이터 처리 (No: Not only), 단지 SQL만 가지고는 데이터를 다 처리할 수 없음의 의미

    <br>

- **Velociry(속도)**

  - **생성 빨라짐**

    데이터 생성 속도가 빨라지면, 데이터가 의미를 가질 시간이 짧아진다. 계속 새로운 데이터가 나오기 때문에 과거 데이터를 가지지 않는다. 데이터의 Life time이 짧아진다.

  - **의미 짧아짐**

    의미를 생각하지 않고, 빨리 '자동화'시켜서 문제를 해결하고 싶어 하는 것.

<br>

<br>

## Data?

- **Digital**

<br>

### Bit(Binary + Digit(0~9)): 0, 1을 사용하는 컴퓨터

### SMS: Simple Message Service

### Pandas의 데이터 스트럭쳐는 R과 비슷하다. 

### Python의 데이터 형태는 거의 정형이고, '비정형'인 것은 '딕셔너리'다.

### 비정형 데이터: 소설, 뉴스 댓글, 후기 등

<br>