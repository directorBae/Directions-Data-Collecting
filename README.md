# Directions Data Collecting
 This repo helps you to collect directions data using Naver and Google API.

 여행지나 식당처럼 실제 장소를 다뤄야 할 때, 하나하나 다 N by N의 길찾기 데이터를 수집하기에는 무리가 있습니다.
 그 데이터의 수가 적다면 충분히 가능하겠지만, 현업 상황처럼 장소의 수가 500개만 넘어가도 상당히 힘들어집니다.
 또한, DB에 새로운 장소가 추가되었을 시 다시 데이터를 수집해야 합니다.

 다만, 시/도의 거점을 격자로 구성하여 미리 데이터를 수집해 둔다면 연산량이 줄어들고,
 새로운 장소가 들어와도 새로운 수집 없이 대략적인 길찾기 데이터의 정보를 얻어올 수 있습니다.

 대략적인 길찾기 데이터의 정보를 얻어오는 과정을 구현합니다.

 Ver2.0에서는 대중교통 밀집도 등을 고려해서 격자의 모양을 바꾸는 방법론을 고민 중입니다.

 When you have to deal with real places like travel destinations or restaurants, it is unreasonable to collect N by N wayfinding data for each one.
 If the number of data is small, it is possible enough, but it becomes quite difficult even if the number of places exceeds 500 as in the current situation.
 Also, data must be collected again when a new location is added to DB.

 However, if data is collected in advance by organizing the bases of the cities into a lattice, the amount of calculation is getting smaller, 
 moreover, even if a new place is collected, rough wayfinding data can be obtained without collecting again.

 It implements the process of obtaining rough pathfinding data information.

 In Ver2.0, we are considering a methodology to change the shape of the grid in consideration of the density of public transportation.