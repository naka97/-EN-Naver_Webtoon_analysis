# (EN)Naver_Webtoon_analysis

- 영어권 네이버 웹툰을 분석하여 구독, 좋아요, 조회수 등의 변수가 랭킹에 미치는 영향을 분석
- 상위권 웹툰과 하위권 웹툰을 비교하고 댓글을 분석하여 공통적인 키워드가 무엇인지 분석

<br></br>

## Team : Today Webtoon
- 김다현 : 배가 고파용 
- 오치헌 : 착해용
- 변웅섭 : 말이 많아용

<br></br>


## Analysis Process

1. 구독, 좋아요, 조회수, 장르, 별점등의 변수에 대한 탐색적 분석을 실시하고 상관관계를 파악 (막대그래프/선그래프/히트맵)<br/>
         - EDA <br/>1) 전체 웹툰에서 어떤 장르가 가장 많은가?<br/>
               2) 가장 좋아요가 많은 웹툰 10개, 적은웹툰 10개<br/>
               3) 가장 조회수가 많은 웹툰 10개, 적은웹툰 10개<br/>
               4) 가장 별점이 높은 웹툰 10개, 적은 웹툰 10개<br/>
               5) 기타 등등...........
               6) 변수간 상관관계 분석 

2. 상위권 웹툰 3개, 중위권 웹툰 3개, 하위권 웹툰 3개를 선정하여 비교

3. 선택한 웹툰의 댓글을 크롤링하여 키워드를 분석 (키워드 빈도수 체크 / 워드클라우드 시각화)
+댓글 감정분석 해보는것도...재미있을듯..?
+장르에 따라 독자들에게 어떤 영향을 미치는지? 감정분석?

<br></br>

## Data Introduce

kaggle : Webtoon Comics Dataset
link : https://www.kaggle.com/datasets/swarnimrai/webtoon-comics-dataset

Naver Webtoon(en)
https://www.webtoons.com/en/dailySchedule
<br></br>

