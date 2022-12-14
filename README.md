# NLP을 이용한 문헌 연구 방법

파이썬을 이용하여 웹스크레이핑을 통해 얻은 상세 서지 정보를 활용하여 문헌 연구를 수행하고 경향을 분석하기 위한 프로젝트입니다.  
<br><br><br>

## 문헌 연구와 글쓰기의 이해
문헌 연구와 글쓰기의 이해를 위한 기초적인 내용을 다룹니다.
또한 자동화된 문헌 연구의 한 가지 방법으로 R-Studio의 bibliometrix Package를 이용한 상세 서지정보 분석 방법도 간단히 소개합니다.
실습에서 사용된 Web of Science의 서지정보 파일은 다음을 통해 다운로드 받을 수 있습니다.
https://drive.google.com/file/d/1IzRK...

또한 과제는 아래의 링크를 통해 제출하시기 바랍니다!
https://forms.gle/7Tiz5oZqeRQNynKH9

[![문헌 연구에 대한 이해](http://img.youtube.com/vi/RdzZBHKzCSI/sddefault.jpg)](https://youtu.be/RdzZBHKzCSI?t=0s) 

<br><br>
## 네이버 및 RISS에서 데이터 가져오기
파이썬에서 제공하는 requests 및 beautifulsoup 라이브러리를 중심으로 웹 스크레이핑하는 예제를 다룹니다.
특히 네이버에서의 뉴스 검색 그리고 한국교육학술정보원의 데이터베이스인 RISS로부터 주제어와 관련된 학술 논문 정보를 검색하는 방법을 주로 다룹니다.

자신이 관심있는 논문 또는 주제를 대상으로 네이버 또는 빅카인즈, RISS로부터 검색해 데이터를 얻는 방법을 수행해 보기 바랍니다.
제출은 아래의 링크를 통해 가능합니다.
https://forms.gle/xsToPiUB8LYeCGyEA

[![파이썬을 활용한 웹스크레이핑](http://img.youtube.com/vi/CT1RB1Tm5sw/sddefault.jpg)](https://youtu.be/CT1RB1Tm5sw?t=0s) 

<br><br>
## 텍스트 전처리와 분류하기
파이썬에서 제공하는 nltk, gensim 그리고 BERT를 이용한 토크나이징과 임베딩을 다룹니다.
또한 비지도학습 기법 중 하나인 LDA(Latent Dirichlet Allocation)을 이용한 사례까지 다룹니다.

자신이 수집한 데이터셋을 활용해서 직접 전처리한 후 LDA를 통해 분석해 보기 바랍니다.
데이터셋과 코드는 아래의 링크를 통해 가능합니다.
https://forms.gle/gYp6Lboj2XGcRq4G7

[![파이썬을 활용한 텍스트 전처리와 분류](http://img.youtube.com/vi/ce-1Uo1nNcg/sddefault.jpg)](https://youtu.be/ce-1Uo1nNcg?t=0s) 

<br><br>
## 수집된 텍스트를 활용한 범주화와 동향 분석
파이썬을 이용한 비지도학습 기반의 분류(K-Means + UMAP + Transformer)에 대해 다룹니다.
각각의 초록에 해당하는 문서를 BERT를 활용해 임베딩한 뒤, UMAP을 이용해 차원 축소(768차원 -> 2차원)를 거치며,
이 데이터들을 비지도학습 기반으로 K-Means clustering을 해 유사한 성격의 연구끼리 묶도록 합니다.
그리고 묶인 연구에 대한 요약은 T5를 이용하도록 구현하였습니다.
[![파이썬을 활용한 범주화와 동향 분석](http://img.youtube.com/vi/oZZKZMTngKo/sddefault.jpg)](https://youtu.be/oZZKZMTngKo?t=0s) 
