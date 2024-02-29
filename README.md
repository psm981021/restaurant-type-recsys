### 👨‍👧‍👧 [Team]


### 💡 [Background]
#### 네이버 플레이스 리뷰 데이터를 바탕으로 한 추천시스템 구현

+ 사용자의 리뷰 이력으로부터 자주 방문하는 음식점을 파악하여 추천에 반영하였습니다.
+ 사용자별로 취향이 있고 이를 군집화 하고자 합니다.
+ 음식점 관련 한국어 리뷰 데이터셋을 구축하고자 하였습니다. (추후 활용)

### 📚 [Stack]

+ Python 
+ Pytorch 
+ Numpy 
+ Pandas
+ Selenium

### 📝 [Features]

+ Selenium을 통해 네이버 플레이스 리뷰 데이터를 크롤링했습니다.
+ Kmeans를 통해 사용자별로 취향이 존재함을 확인하고 이를 군집화 하였습니다.

<p align="center"> <img src = "https://github.com/psm981021/restaurant-type-recsys/blob/main/kmeans.png" width = "50%" ></p>

+ 협업필터링을 통해 추천시스템을 설계하였습니다.

+ Bert4Rec을 통해 방문한 음식점들간의 관계를 파악하여 추천에 반영하고 하였습니다.
<p align="center"> <img src = "https://github.com/psm981021/restaurant-type-recsys/blob/main/BERT4Rec_inference.png" width = "50%" > </p>

+ SASRec을 통해 추천시스템에 있어 단방향으로 음식점의 상관관계를 모델링 하였습니다.
<p align="center"> <img src = "https://github.com/psm981021/restaurant-type-recsys/blob/main/SASRec_inference.png" width = "50%" > </p>


### 🔍 [Link]
https://concise-root-fdd.notion.site/6de6e81bf3eb42c5885f3a8a2313b3ec
