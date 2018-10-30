# MongoDB Forum SEOUL 2018

MongoDB 포럼 서울에서 들은 정보들을 정리한 문서입니다.

## 개최사

 *국내에 MongoDB 한국지사가 어떻게 설립되었는지, 앞으로의 영업 및 기술지원 등은 어떻게 이루어질지에 대한 내용*



 ## MongoDB 회사소개 및 Global case-study ( John hong )

 *MongoDB가 무슨 회사인지, 그리고 고객은 왜 MongoDB를 선택하게 되었는지, 그리고 일부 고객사의 활용 사례에 대해 설명*

- MongoDB가 성공할 수 있었던 이유
  - 데이터를 활용하여 기존에 없던 매출 흐름을 창출
    - 오늘날 변화를 일으키는 기업만이 살아남을 수 있는 만큼 지금의 기업들은 새로운 변화를 일으키기 위해 노력중
    - 최근 모바일 시장의 성장에 따라 사용자는 기업의 모바일 지원을 당연하게 생각하게 됨
    - IOT, AI, 기계학습 등이 이 흐름에 동참하고 있음
  - 앞으로 기업에서 차지하는 소프트웨어 엔지니어링의 중요성은 점점 증가할 것임
    - 이런 변화로부터 기업이 살아남기 위해서는 훌륭한 소프트웨어를 개발해야 할 것으로 기대됨
    - 개발자의 생산성 극대화, 업무 효율성 강화가 기업의 중요한 과제가 되고 있음
    - 디지털 전략이 효과적으로 이용되지 못하는 이유는 데이터를 잘 활용하지 못하기 때문임
  - 데이터를 잘 활용하기 위해서는...
    - 여기저기 분산된 데이터에서 데이터를 찾기 힘들고, 시간이 갈수록 요구되는 성능은 증가됨
    - 이에 알맞은 기술을 활용해야
- 왜 고객들은 MongoDB를 선택했는가
  - 데이터를 가지고 작업하기에 편리하다
    - 쉽고, 빠르고, 유연하며, 다양성이 있다
  - 지능적으로 필요한 부분에 데이터를 넣을 수 있다
    - Availability, Scalability, Workload Isolation, Locality, etc..
      - 지능적으로 데이터 서버를 분산 가능(지연 시간 최소화)
  - 언제 어디서나 데이터를 이용할 수 있는 자유로움이 있다
    - 어떤 클라이언트이던 모든 플랫폼을 지원
    - 일관된 경험을 선사
    - 아마존, Azure 등 클라우드 서버에 MongoDB가 컴퓨팅 파워를 분산할 수 있도록 지원
    - 멀티 클라우드 전략을 통해 고객사를 보호
  - RDB의 문제점
    - 고객마다 가지고 있는 정보가 매우 다르기에 결과적으로 RDB에서는 불필요한 공간이 남게 됨
    - 이는 성능 저하로 이어짐(복잡한 저장 구조는 덤)
    - In MongoDB
      - Naturally maps to objects in code
      - Represent data of any structure
      - strongly typed for ease of processing - over 20 binary encoded JSON
      - Access by idiomatic drivers in all major programming language

- MongoDB의 발전 과정
  - 3.0에서 4.0까지
    - 그래프 프로세싱: 그래프 DB 관련 내용 추가로 범용 DB 구현
    - 여러 플랫폼을 지원
    - 클래스터 간 융통성 강화
    - 몽고디비를 다양한 기능을 지원하는 범용 DB로 사용할 수 있을 것으로 예상됨
    - 몽고디비 모바일
- Atlas
  - 개발 목적으로써의 프리 티어 제공 - 가입 필요
  - 글로벌한 데이터 서비스 가능
  - 백업, 모니터링, 인프로 구축, 확장 등
  - 외부로부터의 위험을 차단할 수 있음
  - 다양한 클라우드 제공자의 서비스를 이용할 수 있음



- 주요 고객 활용 사례
  - MetLife(보험사)
    - 150년 이상의 역사 및 수많은 인수합병으로 보험 상품의 종류가 광범위함
    - 특정 고객에 대한 보험 상품을 추천할 때, 그에 관한 정보가 너무 분산되어 있는 어려움을 겪음
    - MongoDB의 유연한 확장성으로 하나의 통합된 뷰를 통해서 고객에게 서비스할 수 있게 됨
  - 시카고 시
    - 더 똑똑하고 안전한 도시를 만들기 위해서 MongoDB를 사용
    - 유연한 데이터 모델을 통해 분산된 데이터를 하나의 관점으로 묶어 통합된 뷰로 만들고,
      이를 통해 다양한 서비스를 제공할 수 있게 되었음
  - John Deere(미국 농업 서비스 제공 회사)
    - IOT 활용사례 중 하나
    - 단위면적당 생산량을 늘는 데 있어서 센서로 들어오는 데이터를
      MongoDB의 장점과 융합을 통해 좋은 결과를 얻을 수 있었음
  - coinbase
    - 미국의 암호화폐 지갑을 제공하는 회사로, 가상화폐 광풍으로 인해 수요가 폭발적으로 증가
    - Atlas 사용으로 플랫폼 가용성을 높임(신기술을 도입할 때 빠른 시간 내에 구현)

## MongoDB 4.0의 신기능

*트랜지션 지원 확대 및 모바일 지원, 도표 지원 등 신기능 관련 내용들*

## MongoDB를 통한 '뱅크샐러드' 앱 개발

 *뱅크샐러드가 무슨 역할을 하는 앱인지, 그리고 왜 MongoDB를 사용하게 되었는지 등에 관한 내용*

- 유용한 기능들
  - Real Time Dashboard
    실시간으로 쿼리를 검사하여 문제되는 쿼리를 수정
  - MongoDB Atlas
    다양한 클라우드 플랫폼에서 사용
    문제상황 발생시 슬랙이나 이메일 등을 통해서 경고
  - Backup Snapshot
    순간의 실수로 문제가 발생하지 않도록 도움
- Custom Data Pipeline
  - ObjectId를 통해 DB에 부담이 없도록 JSON을 다운받고, 아마존 S3로 업로드 한 뒤
    Athena를 사용



## MongoDB 도입을 위한 제언

Facebook MongoDB Korea Users Group

- 도입하게 된 계기
  - NOSQL에 대한 궁금줄
  - RDBMS의 한계
  - 다양한 OSS와의 연계
- 도입하는 과정
  - RDB보다 좋은 장점 찾기
  - 대체 시도하기
  - 어려웠던 점
    - 이전 버전에서의 성능 저하
    - 병목 현상 발생
    - Map Reduce
  - 대책
    - 최신 버전의 MongoEngine으로 업데이트
    - 서버에 SSD 설치
    - YAML Config 사용
    - Array Embedding
- 성공 사례
  - Beusable - UX Heatmap
  - NTS Chat Bot - 국세상담센터
    카카오톡 이용 챗봇 구
- etc
  - Slack: mongodbkorea.slack.com
    슬랙 가입은 커뮤니티 운영진보고 요청
- 도입 제언
  - 하나의 언어는 완전히 깨우친 개발자
  - RDBMS의 경험이 많은 DBA/Modeler
  - MongoDB University
  - 기반 시설
    - 싸고 많은 수량의 서버 배치
    - 10GB Ethernet
    - More Than Cloud

# 맺음말

- KOLON BENIT?
  - IBM, DELL, Open Sources 등의 사업 영역
  - 뜻밖의 채용 광고?
    - 세일즈
      (영업직??)
    - 