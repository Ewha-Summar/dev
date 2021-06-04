## 문서 요약을 통한 질의 집중적 학습 도움 서비스 *Summar*

### 1) *Summar*란?
: 문서 요약을 통한 질의 집중적 학습 도움 서비스
1. 문서 입력 : 사용자가 요약을 원하는 문서를 입력
2. 문서 요약 : 사용자가 입력한 문장 수에 맞추어 중요 문장 요약
3. 빈칸문제 생성 : 입력한 문서에 따른 빈칸문제 자동 생성 및 채점
4. 질의응답 : 사용자가 입력된 문서에 대한 질문을 하면 자동 답안 생성
5. 오답 노트 & 자가학습 : 문제 유형과 과목에 따른 개인 오답노트 제공 및 스스로 학습이 가능한 자가학습 기능 제공

### 2) *Summar* 시연 영상
- https://youtu.be/L3eeL_0Gx5M

### 3) *Summar* 배포 URL
- https://ewha-summar.github.io/front/

### 4) *Summar*의 목적
COVID-19로 언택트 시대가 도래하면서, 혼자 공부하는 사람이 증가하였다. 하지만, 한국어를 제공하는 서비스는 많지않았고, 한국어 제공을 한다고 하여도, 학습의 질이 낮거나 단순하여 도움이 크게 되지 않았다. 또한, 인공지능이 발전하면서 교육에 도입하려는 시도가 굉장히 많았지만, 기술적으로 어려운 난이도 때문에 현재까지 인공지능을 이용한 교육 서비스가 시중에 많이 없다.
따라서 언택트 시대에 학생들이 스스로 공부할 수 있는 한국어 학습 도움 서비스인 *Summar*를 제작했다.

### 5) System 구조도 & Database schema
- System 구조도

<img width="485" alt="KakaoTalk_20210604_150817864" src="https://user-images.githubusercontent.com/66114269/120763334-124da280-c552-11eb-9ea4-9244919a15e0.png">

- Database schema

![그림1](https://user-images.githubusercontent.com/66114269/120765774-812bfb00-c554-11eb-9a67-f3151eac1e0f.png)


### 6) 기술블로그 소개
- 정아연 https://yeon-code.tistory.com/48
  : TextRank를 이용해서 요약하기
- 최윤재 https://enjoy-studying.tistory.com/37
  : TextRank 기반으로 요약문 생성하기, 빈칸문제 만들기
- 정하늘 https://hneul-dvlp.tistory.com/8
  : 워드 임베딩을 이용한 한글 문서 추출 요약 및 빈칸 문제 생성
- 김지운 https://jeewoon98.tistory.com/4
  : TextRank와 한국어 문서 요약
  

### 7) Reference
- TextRank : https://wikidocs.net/91051
- Word2Vec : https://github.com/Kyubyong/wordvectors
- 형태소 분석 & 개체명 인식 : https://aiopen.etri.re.kr/guide_wiseNLU.php
- 질의응답 : https://aiopen.etri.re.kr/guide_wiseQAnal.php

### 8) License
- Apache License 2.0
