# LLM을 활용한 실전 AI 애플리케이션 개발

## All the Source Codes
* [GitHub Repo](https://github.com/onlybooks/llm)

## Table of Contents

### [1부] LLM의 기초 뼈대 세우기
#### 1장 LLM 지도
1.1 딥러닝과 언어 모델링   
1.2 언어 모델이 챗GPT가 되기까지   
1.3 LLM 애플리케이션의 시대가 열리다   
1.4 LLM의 미래: 인식과 행동의 확장   
1.5 정리   

#### 2장 LLM의 중추, 트랜스포머 아키텍처 살펴보기
2.1 트랜스포머 아키텍처란   
2.2 텍스트를 임베딩으로 변환하기   
2.3 어텐션 이해하기   
2.4 정규화와 피드 포워드 층   
2.5 인코더   
2.6 디코더   
2.7 BERT, GPT, T5 등 트랜스포머를 활용한 아키텍처   
2.8 주요 사전 학습 메커니즘   
2.9 정리   

#### 3장 트랜스포머 모델을 다루기 위한 허깅페이스 트랜스포머 라이브러리
3.1 허깅페이스 트랜스포머란   
3.2 허깅페이스 허브 탐색하기   
3.3 허깅페이스 라이브러리 사용법 익히기   
3.4 모델 학습시키기   
3.5 모델 추론하기   
3.6 정리   

#### 4장 말 잘 듣는 모델 만들기
4.1 코딩 테스트 통과하기: 사전 학습과 지도 미세 조정   
4.2 채점 모델로 코드 가독성 높이기   
4.3 강화 학습이 꼭 필요할까?   
4.4 정리   

### [2부 LLM 길들이기]
#### 5장 GPU 효율적인 학습
5.1 GPU에 올라가는 데이터 살펴보기   
5.2 단일 GPU 효율적으로 활용하기   
5.3 분산 학습과 ZeRO   
5.4 효율적인 학습 방법(PEFT): LoRA   
5.5 효율적인 학습 방법(PEFT): QLoRA   
5.6 정리   

#### 6장 sLLM 학습하기
6.1 Text2SQL 데이터셋   
6.2 성능 평가 파이프라인 준비하기   
6.3 실습: 미세 조정 수행하기   
6.4 정리   

#### 7장 모델 가볍게 만들기
7.1 언어 모델 추론 이해하기   
7.2 양자화로 모델 용량 줄이기   
7.3 지식 증류 활용하기   
7.4 정리   

#### 8장 sLLM 서빙하기
8.1 효율적인 배치 전략   
8.2 효율적인 트랜스포머 연산   
8.3 효율적인 추론 전략   
8.4 실습: LLM 서빙 프레임워크   
8.5 정리   

### [3부] LLM을 활용한 실전 애플리케이션 개발
#### 9장 LLM 애플리케이션 개발하기
9.1 검색 증강 생성(RAG)   
9.2 LLM 캐시   
9.3 데이터 검증   
9.4 데이터 로깅   
9.5 정리   

#### 10장 임베딩 모델로 데이터 의미 압축하기
10.1 텍스트 임베딩 이해하기   
10.2 문장 임베딩 방식   
10.3 실습: 의미 검색 구현하기   
10.4 검색 방식을 조합해 성능 높이기   
10.5 실습: 하이브리드 검색 구현하기   
10.6 정리   

#### 11장 자신의 데이터에 맞춘 임베딩 모델 만들기: RAG 개선하기
11.1 검색 성능을 높이기 위한 두 가지 방법   
11.2 언어 모델을 임베딩 모델로 만들기   
11.3 임베딩 모델 미세 조정하기   
11.4 검색 품질을 높이는 순위 재정렬   
11.5 바이 인코더와 교차 인코더로 개선된 RAG 구현하기   
11.6 정리   

#### 12장 벡터 데이터베이스로 확장하기: RAG 구현하기
12.1 벡터 데이터베이스란   
12.2 벡터 데이터베이스 작동 원리   
12.3 실습: HNSW 인덱스의 핵심 파라미터 이해하기   
12.4 실습: 파인콘으로 벡터 검색 구현하기   
12.5 실습: 파인콘을 활용해 멀티 모달 검색 구현하기   
12.6 정리   

#### 13장 LLM 운영하기
13.1 MLOps   
13.2 LLMOps는 무엇이 다를까?   
13.3 LLM 평가하기   
13.4 정리   

### [4부] 멀티 모달, 에이전트 그리고 LLM의 미래
#### 14장 멀티 모달
14.1 멀티 모달 LLM이란   
14.2 이미지와 텍스트를 연결하는 모델: CLIP   
14.3 텍스트로 이미지를 생성하는 모델: DALL-E   
14.4 LLaVA   
14.5 정리

#### 15장 LLM 에이전트
15.1 에이전트란
15.2 에이전트 시스템의 형태
15.3 에이전트 평가하기
15.4 실습: 에이전트 구현
15.5 정리   

#### 16장 새로운 아키텍처 
16.1 기존 아키텍처의 장단점   
16.2 SSM   
16.3 선택 메커니즘   
16.4 맘바   
16.5 코드로 보는 맘바   

#### 부록 | 실습을 위한 준비사항
A.1 구글 코랩 사용법   
A.2 허깅페이스 토큰   
A.3 OpenAI 토큰