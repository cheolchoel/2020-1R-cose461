# 2020-1R-cose461 ( team 6 )
2020 1R cose461(NLP)

<br/>
<한글><br/><br/>
<Data Description>
"NSMC"는 네이버 영화 리뷰에 달린 별점을 긍정/부정으로 변환한 binary-class 데이터셋입니다.<br/>
주어진 문장을 긍정(1) 혹은 부정(0)으로 분류해야 합니다. <br/>
<File Description>
Train <br/>
학습 데이터 다운로드: https://github.com/e9t/nsmc <br/>
Test <br/>
ko_data.csv - 입력으로 사용한 테스트 파일 <br/>
sample_kaggle_1st.csv - 예측값을 레이블링해 제출한 테스트 파일 <br/>
<br/>
<코드 실행> <br/>
학습 데이터를 다운해서 <br/>
ratings_train.txt 파일과 ratings_test 파일을 각각 <br/>
"/content/drive/My Drive/Colab Notebooks/NLProcssing/COSE461K/nsmc-master/ratings_train.txt" <br/>
"/conent/drive/My Drive/Colab Notebooks/NLProcssing/COSE461K/nsmc-master/ratings_test.txt" <br/>
에 넣어서 코드를 실행시켰다. <br/>
(실행시킬 사용자가 ratings_train.txt 파일과 ratings_test 파일을 원하는 디렉토리에 넣어서 실행시키면 된다.)<br/>

코드형식은 .ipynb 형식으로 주피터 노트북이나 colab 을 이용해서 실행할 수 있다.<br/>




<br/>
<br/>
< 영어 > <br/>
<Data Description>
friends 드라마 대본 데이터로 학습해 8가지 감정 분류를 해낸다.<br/>
  
학습 데이터 다운로드: http://doraemon.iis.sinica.edu.tw/emotionlines/download.html <br/>

< 실행 방법 > <br/>
1. colab notebook으로 노트북 파일을 연다. <br/>
2. google drive mount <br/>
3. /2020 1학기/자연어처리/friends/ 폴더 생성 <br/>

혹은 <br/>

드라이브에 임의의 폴더 생성 후 <br/>
path = "/content/drive/My Drive/2020 1학기/자연어처리/friends" 값을 경로에 맞춰 변경한다. <br/>


4. 다음 파일들을 폴더에 붙여넣기 후 실행한다. <br/>

en_data.csv <br/>
en_sample.csv <br/>
friends_train.json <br/>
friends_dev.json <br/>
friends_test.json <br/>





