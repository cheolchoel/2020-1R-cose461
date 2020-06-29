# 2020-1R-cose461 ( team 6 )
2020 1R cose461(NLP)

<한글>
<Data Description>
"NSMC"는 네이버 영화 리뷰에 달린 별점을 긍정/부정으로 변환한 binary-class 데이터셋입니다.
주어진 문장을 긍정(1) 혹은 부정(0)으로 분류해야 합니다.
<File Description>
Train
학습 데이터 다운로드: https://github.com/e9t/nsmc
Test
ko_data.csv - 입력으로 사용한 테스트 파일
sample_kaggle_1st.csv - 예측값을 레이블링해 제출한 테스트 파일

<코드 실행>
학습 데이터를 다운해서 
ratings_train.txt 파일과 ratings_test 파일을 각각 
"/content/drive/My Drive/Colab Notebooks/NLProcssing/COSE461K/nsmc-master/ratings_train.txt"
"/conent/drive/My Drive/Colab Notebooks/NLProcssing/COSE461K/nsmc-master/ratings_test.txt"
에 넣어서 코드를 실행시켰다. (실행시킬 사용자가 ratings_train.txt 파일과 ratings_test 파일을 원하는 디렉토리에 넣어서 실행시키면 된다.)

코드형식은 .ipynb 형식으로 주피터 노트북이나 colab 을 이용해서 실행할 수 있다.






< 영어 >
<Data Description>
friends 드라마 대본 데이터로 학습해 8가지 감정 분류를 해낸다.
  
학습 데이터 다운로드: http://doraemon.iis.sinica.edu.tw/emotionlines/download.html

< 실행 방법 >
1. colab notebook으로 노트북 파일을 연다.
2. google drive mount
3. /2020 1학기/자연어처리/friends/ 폴더 생성

혹은 

드라이브에 임의의 폴더 생성 후
path = "/content/drive/My Drive/2020 1학기/자연어처리/friends" 값을 경로에 맞춰 변경한다.


4. 다음 파일들을 폴더에 붙여넣기 후 실행한다.

en_data.csv
en_sample.csv
friends_train.json
friends_dev.json
friends_test.json





