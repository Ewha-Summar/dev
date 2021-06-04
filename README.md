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
최근 untact 시대가 도래되며 혼자서 공부를 하는 사람들이 증가함에 따른 학습 도움 서비스의 필요성이 대두되고 있다.
하지만 많은 사람들이 각자 다른 분야의 공부를 하는데에 도움을 줄 수 있는 서비스는 많지가 않다. 문서를 요약해주거나 퀴즈를 만들어주는 서비스는 몇몇 있지만, 한글을 지원하지 않거나 자동으로 문제를 생성해주지 않는다는 한계점이 있었다.

시작하기에 앞서 코로나로 언택트 시대가 도래하면서, 혼자 공부하는 사람이 증가하였습니다. 하지만, 한국어를 제공하는 서비스는 많지않았고, 한국어 제공을 한다고 하여도, 학습의 질이 낮거나 단순하여 도움이 전혀 안되는 상황이었습니다. 또한, 인공지능이 발전하면서 교육에 도입하려는 시도가 굉장히 많았지만, 기술적으로 어려운 난이도 때문에 현재까지 인공지능을 이용한 교육서비스가 시중에 많이 없습니다. 따라서 저희는 언택트 시대에 학생들이 스스로 공부할 수 있는 한국어 학습 도움 서비스인 Summar를 제작하였습니다.  
따라서 많은 사람들이 더 다양한 학습 자료들로 효율적으로 공부할 수 있는 질의 집중적 학습 도움 서비스 *Summar*를 개발하고자 한다.

### 5) System 구조도 & Database schema
- System 구조도

![system구조](https://user-images.githubusercontent.com/66114269/101778175-dbfd1080-3b36-11eb-979d-662ae505e0ef.png)

- Database schema

![db](https://user-images.githubusercontent.com/66114269/101778429-31392200-3b37-11eb-9384-8ba32ad5ff28.png)

### 6) 기술블로그 소개
- 정아연 https://yeon-code.tistory.com/28
  : Summar project의 개요와 text rank, 형태소분석에 대한 기술설명
- 최윤재 https://enjoy-studying.tistory.com/17
  : 한국어 텍스트에 대한 TextRank 과정을 설명
- 정하늘 https://hneul-dvlp.tistory.com/6
  : 워드 임베딩과 이를 이용한 TextRank 및 초기 성능 평가
- 김지운 https://jeewoon98.tistory.com/3
  : TextRank와 형태소 분석 결과 분석
  

### 7) Reference
- TextRank : https://wikidocs.net/91051
- Word2Vec : https://github.com/Kyubyong/wordvectors
- 형태소 분석 & 개체명 인식 : https://aiopen.etri.re.kr/guide_wiseNLU.php
- 질의응답 : https://aiopen.etri.re.kr/guide_wiseQAnal.php

### 8) License
- Apache License 2.0
