# Hana-Zero-Crawling

## Abstract

하나와영 2019 해커톤대회 참가 코드파일

## Theme

소확행

## Members

김민석, 유병각

## Goals

고파스 sofo 게시판에 안암 일대의 음식점 중 랜덤으로 하나를 선택하여, 검색해주도록 하는 프로그램(chromedriver, selenium 이용)
- Data : final.xlsx에 안암 일대의 음식점 데이터(상호명, 주소, 상권지역)이 정리되어 있고, final.pkl은 이를 pickle 파일로 저장
- Code : 고려대 주변 음식점 Dataset을 전처리하는 과정 및 랜덤으로 검색하게 해 주는 코드(Chromedriver와 final.pkl파일이 같은 경로에 있어야 함).

## Dataset 구축과정

고파스 sofo 게시판 크롤링(selenium, BeautifulSoup)을 통해 상호명, 상권위치, 주소 추출 자동화

