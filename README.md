# '한국어 임베딩' 스터디
Ratsgo님의 자연어 처리 저서 '한국어 임베딩' 스터디 기록 저장소

# People
@ YoungYeon Park <br/>
@ MyungHoon Jin <br/>
@ gyungsu min <br/>
@ KwangJune Choi <br/>


# code

본 레파지토리의 디렉토리 및 코드 구조는 다음과 같습니다.

- docker : 도커 환경 구성을 위한 `Dockerfile`이 있습니다. CPU, GPU 버전을 구분합니다.
- docs : 튜토리얼 페이지와 관련한 마크다운 문서 등이 있습니다.
- models : 임베딩 기법 관련 핵심 코드가 모여 있습니다.
- preprocess : 말뭉치 전처리 관련 코드가 모여 있습니다.
- preprocess.sh : 말뭉치 전처리 자동화 스크립트 모음
- sentmodel.sh : 문장 수준 임베딩 자동화 스크립트 모음
- wordmodel.sh : 단어 수준 임베딩 자동화 스크립트 모음

# Calender
| Name                                  | Date       | Reviewer                     |
|---------------------------------------|------------|------------------------------|
| 2. 벡터가 의미를 어떻게 가지게 되는가 | 02/18/2020 | KwangJune Choi, gyungsu min  |
| 3. 한국어 전처리                      | 02/18/2020 | KwangJune Choi, gyungsu min  |
| 4.1 단어수준 임베딩(1)                | 02/25/2020 | gyungsu min , Park YoungYeon |
| 4.2 단어수준 임베딩(2)                | 03/03/2020 | gyungsu min , Park YoungYeon |
| 5. 문장수준 임베딩                    | 03/10/2020 | KwangJune Choi               |
| 5.4 ELMO                              | 03/17/2020 | MyungHoon Jin, gyungsu min   |

# Reference
[NLP_tutorial](https://github.com/graykode/nlp-tutorial?files=1')<br/>
[한국어 임베딩 튜토리얼](https://ratsgo.github.io/embedding/)
