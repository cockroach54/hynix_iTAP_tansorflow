<Requirments>
GPU or CPU with minimum RAM 8GB
Python 3.5.4 Anaconda
libraries: pandas, numpy, sklearn, matplotlib, seaborn, tensorflow, gensim, nltk

<파일 설명>
lyrics_refine.csv - 전처리된 데이터셋, 실험에서 사용
lyrics_w2v_cnn.ipynb - 실험코드, ipython notebook 형태, 해당 코드로 실험 진행
models - 학습된 word2vec 모델이 저장된 폴더, 실험코드와 같은 dir에 있어야 함
(lyrics.csv) - Raw 데이터셋
(lyrics_w2v_preprocessing.ipynb) - raw 데이터셋인 lyrics.csv를 전처리할 때 사용된 코드, 실험코드 실행하는데에 필요 없음
NN_Team Project_20171217.pdf - 발표자료 PDF 형태

<추가>
위 설명에서 ()표시가 되어있는 파일들은 참고용으로 첨부됨, 실험코드 실행을 하는데에는 필요 없음
lyrics_w2v_cnn.ipynb 에서 hyperparameter 바꿔가면서 실험 진행