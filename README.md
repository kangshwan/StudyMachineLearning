# StudyMachineLearning

This repository is for studying machine learning with Python.

>1장-Intro&FirstApp

1장에서 가볍게 붓꽃을 구별짓는 간단한 훈련을했다

지도학습을 하려면 각 데이터 들을 구분 지을수 있는 것들이 최대한 명확하게 구분되어야 할것같다(?)

k-최근접 이웃 알고리즘(k-Nearest Neighbors, 이하 k-NN)을 사용했다.
객체를 생성할때 가까운 몇개의 이웃을 찾을지 정해줄수 있다.

ex)'''knn = KNeighborsClassifier(n_neighbors = num)'''

k-NN을 사용하려면 명확하게 알고있는 데이터가 필요하다!(물론 지도학습이라면 명확하게 알고있는 데이터가 있어야 하겠지만 말이다)
