# 🚲 서울시 공공자전거(따릉이) 데이터 분석 프로젝트

본 프로젝트는 **서울시 공공자전거 이용 데이터**를 기반으로 이용 현황 및
패턴을 분석하는 Streamlit 기반 웹 애플리케이션입니다.

## 📌 프로젝트 소개

서울시 공공자전거 **따릉이** 데이터를 분석하여 대여소별 이용량,
이용시간, 성별/연령대별 통계 등을 제공합니다.

## 🛠 사용 기술

-   Python
-   Streamlit
-   pandas, seaborn, matplotlib, plotly

## 📂 프로젝트 구조

    📁 프로젝트 폴더
     ├── bigdata.py
     ├── bic.csv
     ├── 따릉이.png
     ├── 서울시.jpg
     ├── style.css
     └── README.md

## ▶ 실행 방법

### 1. 패키지 설치

``` bash
pip install streamlit pandas seaborn matplotlib plotly
```

### 2. 실행

``` bash
streamlit run bigdata.py
```

## 📊 주요 기능

-   대여소별 데이터 조회
-   이용건수 TOP10 분석
-   이용시간 TOP10 분석
-   성별/연령대별 통계 분석

## 📁 데이터 출처

서울시 공공데이터포털
