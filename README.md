# 🕸 Python Selenium Data Crawling & Analysis Project

이 프로젝트는 Python과 Selenium을 이용해 다양한 웹 데이터를 자동 수집하고, 이를 바탕으로 실생활과 관련된 **사회 현상, 소비 트렌드, 지역 인프라** 등을 분석한 실습형 포트폴리오입니다.

---

## 📌 수집한 데이터 주제 및 설명

| 주제 | 설명 | 관련 파일 |
|------|------|-----------|
| 🚗 교통사고 통계 | 도로교통공단에서 월별 교통사고 발생 건수 크롤링 및 시각화 | `py11_교통사고유형별발생분석v1.py` |
| 🎥 CCTV 설치 현황 | 지자체별 CCTV 설치 개수 데이터 수집 | `py11_방범용 CCTV 위치분석.py` |
| 💼 연령별 취업자 수 | 통계청의 연령대별 취업 통계 자동 수집 및 그래프화 | `py11_연령별취업자수관계.py` |
| 🛍️ 온라인 쇼핑몰 분석 | 온라인 쇼핑 카테고리별 인기 품목 및 금액 비교 분석 | `py11_온라인쇼핑몰 매출관계분석.py` |
| ✈️ 인천공항 이용자 수 | 공항 월별 이용객 수 통계 크롤링 및 트렌드 분석 | `py11_인천공항.py` |
| 🚇 지하철 이용자 수 | 서울시 지하철 노선별 시간대별 이용 현황 | `py11_지하철이용현황분석.py` |
| 🧠 청소년 정신건강 | 보건복지부 청소년 정신건강 실태조사 자동 수집 | `py11_청소년정신건강.py` |
| 📷 인스타그램 크롤링 | 셀레니움으로 인스타 해시태그/지역기반 포스트 이미지 및 텍스트 수집 | `py14_HDFS_자동화크롤링(인스타).py` |
| ⛽ 주요소 위치 및 유가 분석 | 지역별 주요소 위치 및 휘발유 가격 비교 분석 | `py14_HDFS_자동화크롤링(주유가격)2.py` |
| ☕ 스타벅스 위치 분석 | 지역별 스타벅스 매장 분포 및 밀도 분석 | `x_py13_셀레니움크롤링1u.py` |

---

## 📊 시각화 예시

### ✅ 교통사고 발생 추이

![image](https://github.com/user-attachments/assets/4d0a3782-3138-4e43-bef2-ccef7c0ab669)


### ✅ CCTV 설치 현황

![image](https://github.com/user-attachments/assets/2abff92e-8181-432e-9f8a-62d4a4fc605e)


### ✅ 연령별 취업자 분석

![image](https://github.com/user-attachments/assets/de88d028-06bb-42a7-820c-2a80dbef16d7)


### ✅ 온라인 쇼핑몰 분석

![image](https://github.com/user-attachments/assets/6493d9e1-d3d0-47ad-8e78-0d2605752fb9)


### ✅ 인천공항 이용자 수 분석

![image](https://github.com/user-attachments/assets/61219a28-9350-49e3-8c1c-8c79a2ed3be3)


### ✅ 부산 지하철 이용자 수

![image](https://github.com/user-attachments/assets/aedab7c8-caa9-4b48-a2b2-398c9b13c65f)


### ✅ 휘발유 가격 지역별 비교

![image](https://github.com/user-attachments/assets/10cdc5e3-2f8c-469c-9735-31b7cce0c07d)


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


📄 데이터 출처
 - 도로교통공단

 - 공공데이터포털

 - 서울시 열린데이터광장

 - 통계청 KOSIS

 - 한국석유공사 오피넷

 - 스타벅스 매장정보 페이지

 - 인스타그램 공개 웹 페이지


