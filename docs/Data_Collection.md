# 기상청 API 허브: 서울 주요 관광지 기후 통계

## 개요
- **데이터 소스**: 공공데이터포털 기상청_관광코스별 관광지 상세날씨 조회 지점 정보
- **파일**: seoul_tour_hotspot.csv
- **관광지 수**: 서울시내 135개 관광지
- **API 위치**: [기상청 API 허브](https://apihub.kma.go.kr/) > 지상관측 > 기후통계

## 데이터 조회 항목

### 1. 기온 기후통계 데이터
- **Spot_id**: 관광지 고유 식별자
- **YMD**: 연월일
- **STN_ID**: 지점 번호
- **LAT**: 위도
- **LON**: 경도
- **ALTD**: 고도
- **TA_DAVG**: 일 평균 기온 (°C)

### 2. 바람 기후통계 데이터
- **TMA**: 시간
- **STN_ID**: 지점 번호
- **LAT**: 위도
- **LON**: 경도
- **ALTD**: 고도
- **WS_DAVG**: 일 평균 풍속 (m/s)
- **WS_MAX**: 일 최대 풍속 (m/s)
- **OCDT_WS_MAX**: 일 최대 풍속 발생 시간 (시간)

### 3. 습도 기후통계 데이터
- **TMA**: 시간
- **STN_ID**: 지점 번호
- **LAT**: 위도
- **LON**: 경도
- **ALTD**: 고도
- **RHM_AVG**: 평균 상대 습도 (%)
- **RHM_MIN**: 최소 상대 습도 (%)

### 4. 강수량 기후통계 데이터
- **TMA**: 시간
- **STN_ID**: 지점 번호
- **LAT**: 위도
- **LON**: 경도
- **ALTD**: 고도
- **RN_DSUM**: 합계 강수량 (mm)
- **RN_MAX_1HR**: 1시간 최다 강수량 (mm)
- **RN_MAX_1HR_OCUR_TMA**: 일 1시간 최다 강수량 발생 시각 (시간)