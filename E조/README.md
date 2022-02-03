
# DSL7기 EDA (2022. 01. 27.)
___
## E팀 : 황다연, 이승재, 박지은, 김찬영, 전재현

![title](https://github.com/jayl-ee/7th_EDA/blob/main/E조/ppt1.png) 
___
## Data
___
* World Happiness Report (Kaggle) [click here](https://www.kaggle.com/unsdsn/world-happiness?select=2017.csv)
* Additional data from the official WORLD HAPPIENESS REPORT [website](https://worldhappiness.report/faq/) -> data of year 2020 & 2021
- you may get the data from "APPENDICES & DATA" in each reports

## 분석 목적
___
* 행복지수에 영향을 주는 요인을 알아내고, 세부적으로 일부 나라들의 특성을 분석해봄.
* 분석 국가 및 지역 : 서유럽, 덴마크, 대한민국, 라틴 아메리카, 일본

## Description 
___
### visualization(Chan Young).ipynb
* 각 지역별 correlation matrix
* * 라틴아메리카 correlation matrix
* * 라틴아메리카 vs 베네수엘라 행복랭킹 변화
* * 라틴아메리카 6개 변수 변화 그래프
* * 라틴아메리카 vs 베네수엘라 6개 변수 변화 비교 그래프
* * 라틴아메리카 vs 베네수엘라 trust 비교 그래프

* 대한민국 correlation matrix
* * 한국 vs 라틴아메리카 Economy, 행복랭킹 변화 비교 그래프
* * 한국 vs 라틴아메리카 6개 볌수 변화 비교 그래프

* 전세계 지역 행복순위 변화 비교 그래프
* * 서유럽 correaltion matrix
* * 서유럽 vs 중위권 지역 6개변수 비교 그래프
* * 서유럽 vs 한국 6개 변수 비교그래프

### World Happiness Report_Korea.ipynb
* 대한민국 vs 모든 국가 평균
* * 행복순위, 행복지수 추이 비교
* * 6개 변수 변화 그래프 비교

* 대한민국 vs 일본
* * 행복순위 비교 (비슷한 것으로 파악)
* * 6개 변수 변화 그래프 비교

* 대한민국 correlation matrix 분석
* * 한국의 correlation vs 모든 국가 평균의 correlation 비교
* * 한국의 Economy와 Happiness Score의 변화 비교 (음의 상관관계 확인)

* 대한민국 vs 한국보다 Economy 낮지만 Happiness Rank 높은 나라
* * 7개년 동안 계속 그 특성을 유지한 15개국 추출 및 시각화 (라틴 아메리카의 비중이 높음을 파악)
* * 6개 변수 변화 그래프 비교

### Overall_Visualization.ipynb
* 전세계의 전반적인 경향성
* * 2015년부터 2019년까지 각 연도의 전세계 correlation matrix
* * 전 기간 평균의 전세계 correlation matrix

* 전세계 속 각 region의 경향성
* * 2015년부터 2019년까지 각 region의 요소별 시계열 분석
* * 전 기간 각 region의 요소별 평균

### about_Denmark.ipynb
* Denmark
* * Denmark의 correlation matrix
* * Denmark의 각 요소별 시계열 분석
    
* Western Europe 속의 Denmark
* * Western Europe과 Denmark의 correlation matrix 비교
* * Western Europe과 Denmark의 각 요소별 시계열 분석 및 비교
    
* 행복지수 순위가 비슷한 국가들 속의 Denmark
* * 행복지수 순위가 비슷한 국가들과 Denmark의 correlation matrix 비교
* * 행복지수 순위가 비슷한 국가들과 Denmark의 각 요소별 시계열 분석 및 비교

### World_Happiness_Report_Japan,_happiness_map,_top30_vs_bottom30.ipynb
* 일본의 행복 지표
* * 각 feature의 상관계수, 행복지수 및 순위 변동성
* * 각 feature별 변동성
* * 일본과 Eastern Asia 국가 비교
* * 일본과 비슷한 순위의 10개 국가 비교 

* Region별 행복지수 지도 시각화

* 행복지수 상위 30개국, 하위 30개국 선정
* * 각 국가의 Region별 분포도
* * 각 feature의 상관계수 비교
* * 각 feature의 지수 비교
