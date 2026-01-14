# seoul-bike
서울 공공데이터인 서울특별시 공공자전거 이용정보를 분석해서 데이터 시각화한 결과입니다.


### 사용 데이터
서울시 공공자전거 이용정보(시간대별)
링크: https://data.seoul.go.kr/dataList/OA-15245/F/1/datasetView.do
서울시 공공자전거 대여소 정보
링크: https://data.seoul.go.kr/dataList/OA-13252/F/1/datasetView.do


## 파일 설명

### 0_load_data
최초에 데이터를 불러오고 확인한 ipynb입니다.
원본 csv를 복사해서 usage_time과 usage_stations로 복사했습니다.
이후 수동으로 열 이름을 수정한 뒤 1_understanding 으로 진행했습니다.

### 1_understanding
데이터를 받아오고, 결측치 및 열 정보를 확인하며 데이터에 대해 이해한 ipynb입니다.
결측치 처리 방법 및 예외값 처리(handling) 방법을 결정했습니다.

### 2_visualizaiton
데이터를 가공한 후 시각화한 ipynb입니다.
stacked bar, heatamp 등으로 데이터를 받아왔습니다.

## 실행
github repository 특성 상 25MB가 넘는 파일에 대한 업로드가 허용되지 않습니다.
모든 실행 결과와 시각화 자료는 pdf에 담겨져 있습니다.
같은 환경에서 실행이 필요한 경우 25년 6월 기준 자료를 공공데이터에서 다운로드받아 실행하시면 됩니다.
