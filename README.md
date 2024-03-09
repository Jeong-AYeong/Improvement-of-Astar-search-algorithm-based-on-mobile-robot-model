# Improvement-of-Astar-search-algorithm-based-on-mobile-robot-model
이동로봇모델기반 A* 탐색 알고리즘의 개선

  
## 💻 Abstract
이동로봇의 활용은 로지스틱 분야의 창고관리에서 서비스 분야의 식당 홀서빙까지 다양하게 활용 범위를 확대시켜 나가고 있다. 이동로봇의 경로탐색은 보통 A* 탐색 알고리즘이 최단 경로 탐색을 위해 사용되고 있지만, 이동로봇모델을 고려하여 경로를 탐색하고 있지 않기 때문에 탐색된 결과를 바로 이동로봇에 적용하기 곤란한 경우가 많다. 이에 본 연구에서는 A* 탐색 알고리즘에 이동로봇의 모델을 평가함수로 사용하여 기존 A* 탐색 알고리즘을 개선시키는 것을 목적으로 하였다. 특히, 본 연구에서는 이동로봇이 90도 이상 회전해야 하는 이동구간을 최소각도 이하로 회전할 수 있도록 제안한 방법을 통하여 A* 탐색 알고리즘을 개선하였다. 회전각도가 크게 되면 로봇의 직진이동 속도를 감속시켜야 하거나 경우에 따라서는 완전히 멈춘 후 다시 출발해야 한다. 하지만, 회전 각도를 최소 각도 이하로 개선하게 되면 로봇의 직진이동 속도 감속 폭을 최소로 할 수 있게 되어 로봇의 이동 효율성을 향상시킬 수 있게 된다. 본 연구의 알고리즘 개선에 사용한 함수는 회전각도에 따른 가중치 값을 달리하여 회전을 최소화하도록 하였다. 적용 결과 90도 회전 각도를 최소 각도인 45도로 변경하여, 제안한 알고리즘 개선방법이 이동로봇의 경로 생성 문제의 효율 개선에 도움이 되는 것을 확인하였다.
<br>

  
## 🔧연구목적
![연구목적](https://github.com/Jeong-AYeong/Improvement-of-Astar-search-algorithm-based-on-mobile-robot-model/assets/87751593/71c588bb-4a91-4873-b41a-5ac8096f948f)
회전이 적은 경로가 로봇의 안정성과 제어 용이성에서 효율적이기 때문에 휴리스틱 함수 변경과 평가함수 적용으로 회전이 적은 경로를 생성해보고자 함.  


## 🔎 기존 A* algorithm
![기존알고리즘](https://github.com/Jeong-AYeong/Improvement-of-Astar-search-algorithm-based-on-mobile-robot-model/assets/87751593/a4901254-193e-417d-b2df-e57ec9d18cfa)


## 🎥 개선된 A* algorithm Demo
![개선된알고리즘](https://github.com/Jeong-AYeong/Improvement-of-Astar-search-algorithm-based-on-mobile-robot-model/assets/87751593/0257b196-7c6c-48c1-a636-8ab8b0cd2a46)
* 이동로봇의 효율을 저해하는 90도 회전이 줄어들어 더욱 효율적인 경로가 생성




## 🔗실행방법
![prize](https://github.com/Jeong-AYeong/Improvement-of-Astar-search-algorithm-based-on-mobile-robot-model/assets/87751593/a953a5cd-1b3d-46b0-be7f-5e6fd4c9950f)
