# 🕸 Python Selenium Data Crawling & Analysis Project

이 프로젝트는 Python과 Selenium을 이용해 다양한 웹 데이터를 자동 수집하고, 이를 바탕으로 실생활과 관련된 **사회 현상, 소비 트렌드, 지역 인프라** 등을 분석한 실습형 포트폴리오입니다.

---

## 📌 수집한 데이터 주제 및 설명

| 주제 | 설명 | 관련 파일 |
|------|------|-----------|
| 🚗 교통사고 통계 | 도로교통공단에서 월별 교통사고 발생 건수 크롤링 및 시각화 | ![image](https://github.com/user-attachments/assets/9be3433f-b928-4aa0-bac9-06ff7673b5b0)
 |
| 🎥 CCTV 설치 현황 | 지자체별 CCTV 설치 개수 데이터 수집 | `cctv_status_scraper.py` |
| 💼 연령별 취업자 수 | 통계청의 연령대별 취업 통계 자동 수집 및 그래프화 | `employment_by_age.py` |
| 🛍️ 온라인 쇼핑몰 분석 | 온라인 쇼핑 카테고리별 인기 품목 및 금액 비교 분석 | `shopping_mall_analysis.py` |
| ✈️ 인천공항 이용자 수 | 공항 월별 이용객 수 통계 크롤링 및 트렌드 분석 | `airport_usage_scraper.py` |
| 🚇 지하철 이용자 수 | 서울시 지하철 노선별 시간대별 이용 현황 | `subway_usage.py` |
| 🧠 청소년 정신건강 | 보건복지부 청소년 정신건강 실태조사 자동 수집 | `youth_mental_health.py` |
| 📷 인스타그램 크롤링 | 셀레니움으로 인스타 해시태그/지역기반 포스트 이미지 및 텍스트 수집 | `instagram_auto_crawler.py` |
| ⛽ 주요소 위치 및 유가 분석 | 지역별 주요소 위치 및 휘발유 가격 비교 분석 | `gas_station_price_analysis.py` |
| ☕ 스타벅스 위치 분석 | 지역별 스타벅스 매장 분포 및 밀도 분석 | `starbucks_location_analysis.py` |

---

## 📊 시각화 예시

### ✅ 교통사고 월별 발생 추이

![교통사고 시각화](images/traffic_chart.png)

### ✅ 쇼핑몰 인기 품목 비율

![쇼핑몰 분석](images/shopping_barplot.png)

### ✅ 휘발유 가격 지역별 비교

![주유소 분석](images/gas_price_comparison.png)

### ✅ 스타벅스 매장 밀도 지도

![스타벅스 밀도](images/starbucks_density_map.png)

---

## 🛠 사용 기술

- Python 3.x
- Selenium (웹 크롤링 자동화)
- BeautifulSoup (HTML 파싱)
- Pandas, NumPy (데이터 처리)
- Matplotlib, Seaborn (시각화)
- Folium (지도 시각화)
- Jupyter Notebook

---

## 🚀 실행 방법

1. ChromeDriver 설치 (크롬 브라우저 버전에 맞게)
2. 가상환경 및 라이브러리 설치

```bash
python -m venv venv
source venv/bin/activate   # (Windows는 venv\Scripts\activate)
pip install -r requirements.txt

