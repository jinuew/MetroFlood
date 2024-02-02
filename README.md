# MetroFlood
서울시 동작구 지하철 침수 위험도를 분석함


포스터:
https://github.com/jinuew/MetroFlood/blob/c11aa442ad63587f354d807757af17d6e6709b32/MetroFloodPoster.pdf


데이터 구성
1. 침수 이력 조회
2. 인근 침수 이력 조회(서울특별시 침수 흔적도 병합)
3. 1m_DEM.tiff 활용
4. 강수 시뮬레이션 지도 활용

데이터 1,2,3 각각 Min-Max 정규화 후 최대 3점 만점의 데이터 분석
강수 시뮬레이션 지도는 홍수휘험지도정보시스템의 웹 지도를 QGIS WMS 기능을 통해 불러온 뒤 래스터화 -> 벡터화 -> 격자에 대입 과정을 통해 분석 가능한 데이터로 변환
