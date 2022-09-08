# 추석 교통 소요시간 예측 프로젝트

## 개요
* 본 프로젝트는 KT AIVLE SCHOOL에서 진행한 추석 교통 소요시간 예측 프로젝트입니다.
* 추석전일(22.9.9(금)) 12시(정오) 고속도로 서울TG출발→부산TG도착 소요시간을 예측합니다.
* 한국도로공사 "도시간소요시간(서울~주요도시)"제공 추석 전일(22.9.9) 12시 정오 고속도로 서울-부산 이동시간 최근접 소요시간 예측차를 달성해야 합니다.
* 한국도로공사 고속도로 공공데이터 포털의 도시간 소요시간(서울-주요도시) 데이터를 크롤링하여 사용하였습니다.

## 패키지 사용

<p align="center">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=NumPy&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=SciPy&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/scikit-learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/JSON-000000?style=flat-square&logo=JSON&logoColor=white"/></a>&nbsp
  <br>
    <img src="https://img.shields.io/badge/-statsmodel-green"/></a>&nbsp
    <img src="https://img.shields.io/badge/%20-request-black"/></a>&nbsp
    <img src="https://img.shields.io/badge/-math-black"/></a>&nbsp
    <img src="https://img.shields.io/badge/-itertools-black"/></a>&nbsp
    <img src="https://img.shields.io/badge/-catboost-yellow"/></a>&nbsp
    <img src="https://img.shields.io/badge/-byes_opt-blueviolet"/></a>&nbsp
    
</p>

## 파일 구조
```
📦KT.CHUSOK
 ┣ 📂데이터와 결과
 ┃ ┣ 📜data.csv
 ┃ ┣ 📜result.csv
 ┃ ┗ 📜target.csv
 ┣ 📂분석설명서
 ┃ ┣ 📜AI 부산경남 8반 안중찬_분석설명서.pdf
 ┃ ┗ 📜AI 부산경남 8반 안중찬_분석설명서.pptx
 ┗ 📜AI 부산경남 8반 안중찬_분석데이터 결과.ipynb
```

## 파일 설명
- AI 부산경남 8반 안중찬_분석데이터 결과.ipynb
    - 프로젝트에 이용한 파이썬 코드들이 담겨있습니다.
- AI 부산경남 8반 안중찬_분석설명서.pdf,pptx
    - 분석과 관련된 내용을 담고있습니다. pdf, pptx 2개의 버전이 존재합니다.
- data.csv
    - 분석에 사용된 데이터입니다.(2020년~2022년 설날,추석 교통 소요시간(1시간단위, 연휴 전후 3일)
- target.csv
    - 예측에 사용된 데이터입니다.(2022년 추석전일 0시~23시)
- result.csv
    - 예측 결과입니다.

## 문의사항
* email : ajc227ung@gmail.com

