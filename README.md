# '한국어 임베딩' 스터디
Ratsgo님의 자연어 처리 저서 '한국어 임베딩' 스터디 기록 저장소

# People
@ YoungYeon Park
@ MyungHoon Jin
@ gyungsu min
@ KwangJune Choi


# code

본 레파지토리의 디렉토리 및 코드 구조는 다음과 같습니다.

- docker : 도커 환경 구성을 위한 `Dockerfile`이 있습니다. CPU, GPU 버전을 구분합니다.
- docs : 튜토리얼 페이지와 관련한 마크다운 문서 등이 있습니다.
- models : 임베딩 기법 관련 핵심 코드가 모여 있습니다.
  - bert : BERT 모델 (저자 original 코드)
  - bilm : ELMo 모델 (저자 original 코드)
  - swivel : Swivel 모델 (저자 original 코드)
  - xlnet : XLNet 모델 (저자 original 코드)
  - sent_eval.py : 문장 임베딩 평가 코드
  - sent_utils.py : 문장 임베딩 학습 관련 유틸
  - train_elmo.py : ELMo 프리트레인 코드 (저자 original 코드, 하이퍼파라미터 일부 수정)
  - tune_utils.py : 임베딩 파인튜닝 관련 유틸
  - visualize_utils.py : 임베딩 시각화 관련 유틸
  - word_eval.py : 단어 임베딩 평가 코드
  - word_utils.py : 단어 임베딩 학습 관련 유틸
- preprocess : 말뭉치 전처리 관련 코드가 모여 있습니다.
  - dump.py : 원시 말뭉치(raw corpus)를 1개 라인(line)이 1개 문서인 순수 텍스트 파일로 변환하는 유틸
  - mecab-user-dic.csv : 은전한닢(mecab) 형태소 분석기의 사용자 사전을 추가하기 위한 입력 파일
  - supervised_nlputils.py : KoNLPy, Khaiii 등 지도학습 기반 형태소 분석기 유틸
  - unsupervised_nlputils.py : soynlp, sentencepiece 등 비지도학습 기반 형태소 분석기 유틸
- preprocess.sh : 말뭉치 전처리 자동화 스크립트 모음
- sentmodel.sh : 문장 수준 임베딩 자동화 스크립트 모음
- wordmodel.sh : 단어 수준 임베딩 자동화 스크립트 모음


# Reference
[NLP_tutorial](https://github.com/graykode/nlp-tutorial?files=1')
[한국어 임베딩 튜토리얼](https://ratsgo.github.io/embedding/)
