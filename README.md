### 👨‍👧‍👧 [Team]
<p align="center">
  <img src="https://github.com/psm981021/restaurant-type-recsys/blob/main/jpg/seongbeom.webp" width="20%" alt="Seongbeom" />
  <img src="https://github.com/psm981021/restaurant-type-recsys/blob/main/jpg/chanbin.webp" width="20%" alt="Chanbin" />
  <img src="https://github.com/psm981021/restaurant-type-recsys/blob/main/jpg/jiwon.webp" width="20%" alt="Chanbin" />
</p>

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

<p align="center"> <img src = "https://github.com/psm981021/restaurant-type-recsys/blob/main/jpg/kmeans.png" width = "50%" ></p>

+ 협업필터링을 통해 추천시스템을 설계하였습니다.

+ Bert4Rec을 통해 방문한 음식점들간의 관계를 파악하여 추천에 반영하고자 하였습니다.
<p align="center"> <img src = "https://github.com/psm981021/restaurant-type-recsys/blob/main/jpg/BERT4Rec_inference.png" width = "50%" > </p>

+ SASRec을 통해 추천시스템에 있어 단방향으로 음식점의 상관관계를 모델링 하였습니다.
<p align="center"> <img src = "https://github.com/psm981021/restaurant-type-recsys/blob/main/jpg/SASRec_inference.png" width = "50%" > </p>

### 👨‍🎓 [What I learned]

+ 협업 필터링부터 트랜스포머 기반 모델까지 유사성을 기반으로 하는 다양한 모델을 시도해 볼 수 있었습니다.
+ 사용자 리뷰 군집화를 통해 간접적으로 취향을 파악할 수 있었습니다.
+ 추천 시스템에서 동일한 음식점을 여러 번 방문하더라도 순서가 다르면 그 경험이 다르게 평가될 수 있다는 사실을 확인했습니다.

### 🤦 [Future Work]

+ 리뷰 텍스트에 대한 감성분석의 결과를 통해 음식점에 대한 평가를 수치화하고, 이를 추천 시스템에 반영하려고 합니다.
+ SASRec 모델에서 Negative Sampling을 더 효과적으로 수행하여 학습 시 후보군을 보다 특정화하고자 합니다.
+ Data Augmentation을 통해 Contrastive Learning을 활용하여 실험하고자 합니다.


### 🔍 [Link]
https://concise-root-fdd.notion.site/6de6e81bf3eb42c5885f3a8a2313b3ec




