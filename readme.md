# 19-1 YBIGTA Conference: 가사로 분석하는 사회

시대별로 유행했던 노래의 가사를 당시 시대상과 연관지어 분석하고 Web으로 시각화한 프로젝트

### 분석 툴
* Python
* JavaScript
##

### 데이터셋
* 벅스 뮤직 55년간(1964~2018) 벅스 차트 연간 1-100위
* 51년간(1965-2015) 빌보드차트 연간 1-100위
##

### 사용 패키지 및 사용 기법
* Selenium
* Konlpy
* Matplotlib
* Seaborn
* TF-IDF: 어떤 단어가 특정 문서 내에서 얼마나 중요한 것인지를 나타내는 통계적 수치 
	* TF: 특정한 단어가 특정 문서 내에서 얼마나 자주 등장하는지를 나타내는 수치
	* DF: 특정 문서군 내에서 특정한 단어가 등장하는 문서의 수를 나타내는 수치
	* IDF: DF의 역수, 값이 높을 수록 해당 문서군 내에서 그 단어가 흔하게 쓰이지 않음을 나타냄. (등장하는 문서 내에서 단어가 특별한 의미를 가지게 됨.)
* H-P Point: 단어 빈도수 순위와 빈도수가 일치하는 지점을 나타냄.  


### Step

1. 다양한 기준으로 구분해 시대별 가사 양상 분석
2. 분석 결과를 차트, wordcloud 등 다양한 형태로 시각화
3. Web 상에 분석 결과 interactive하게 구현