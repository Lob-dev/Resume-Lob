
# Back-end Developer. Lob

<br/>

# 🏠 About Me.

**이름**       :   김석현

**나이**       :   24세 (1998.01)   

**성별**       :   남

**대학 - 전공**    :   동서울대학교 컴퓨터 정보학과

**Email**      :   coffeescript@kakao.com




<br/>


# 👋🏻 Introduce.



기술, 프레임워크에 대하여 구현에만 집중하는 것이 아니라 동작 원리와 흐름을 기반으로 학습하고, 좋은 설계와 코드 등을 찾아보며 이전에 작성했던 코드보다 더 나은 것을 만들기 위해 노력하는 개발자입니다.

카카오톡, 페이스북, 클럽하우스 등에 존재하는 오픈 커뮤니티들에서 여러 지식과 경험을 듣고 배우며, 여러 문서와 기술 블로그의 Best Practice를 참고하여 성장하고 있습니다. JPA, Docker, Database, Kotlin 등 다양한 기술에 관심을 가지고 있으며 우선 순위를 산정하여 차근차근 학습하고 있습니다. 공부한 내용들은 빠짐없이 정리하여 복습하고, 지식공유를 위해 기록해둡니다.

<br/>

- **[사이드로 진행하는 신입 개발자의 자바, 스프링 학습 자료 [링크]](https://github.com/Lob-dev/Junior-Back-end-Developer-Concepts)**
- **[개인 공부 일지 [링크]](https://www.notion.so/Lob-Junior-Developer-be065ebcc7404b17ba74ffc244203912)**
- **[기술적으로 고민한 내용들을 정리하는 블로그 [링크]](https://lob-dev.tistory.com/)**

<br/>


# 👨🏻‍💼 Work Experience.

<br/>

## **[-------]**

### **Back-end Developer**

- **2021-03-08 ~ (현재)**

### **관리자 CMS API 개발 진행 및 **

- Swagger를 이용하여 구현한 API에 대해 문서화를 진행
- Docker를 통해 Local DB를 생성하여 API를 테스트하고 Flyway를 통해 DB 형상 관리
- Spring Boot 2.0.x, MyBatis, MSSQL 사용

<br/>

### **OTT 사용자, 관리자 API 개발 진행**

- JPA, QueryDSL을 이용한 엔티티 구성 및 개발 진행
- 로컬 개발 환경에서는 Docker를 통해 RabbitMQ, Redis, Mysql를 통해 개발 진행
- Spring Boot 2.0.x, Hibernate, QueryDSL, Mysql 사용

<br/>

# 🛂 Portfolio.

<br/>

# 🚀 [Short Term](https://github.com/Lob-dev/Short-Term).

### **URL을 특정 문자열로 단축하여 제공하는 단축 URL 프로젝트.**

- **21.04.29 ~ 21.05.22**
    - Base62 Encoder와 XOR Cipher를 사용하여 Short URL을 생성
    - Redis를 통해 Short URL과 Target URL을 매핑하여 캐싱하고 클라이언트에게 값을 반환
    - TestContainers를 이용하여 실제 운영 환경과 최대한 유사하게 통합 테스트를 구성 및 실행
    - Spring Boot, JPA, Docker, TestContainers, Redis 사용

<br/>

# 🙍🏻‍♂️ [Somaeja](https://github.com/Lob-dev/somaeja).

## **지역 정보 물품 거래 플랫폼 RESTful API 서버 프로젝트.**

- **20.11.20 ~ 21.03.01**
    - RESTful 규약을 준수하여 URI 설계와 API Spec(HTTP Method, Status Code)을 만족하는 API 개발
    - 민감한 설정 정보 보호를 위해 Jasypt Library를 이용해 설정 파일 암호화
    - Local Session 방식의 Session 정보의 동기화와 발생 네트워크 트래픽 등을 최소화하기 위해 JWT를 통한 State-less 방식으로 고도화 진행
    - SFTP를 이용한 build-copy-paste-execute 수동 방식을 Git Branch와 Jenkins를 연동하여 클릭 한번으로 되도록 변경
    - Spring Boot, Web, Mybatis, NCP, AWS EC2, Github, Jenkins 사용

<br/>

# 👨🏻‍💻 Skills.

<br/>

## Mind & Communication.

- **점진적인 계획과 목표를 설정하고 달성하는 방식으로 성장하려 합니다.** 이를 통한 성취감을 원동력 삼아 나아가고 있으며, 이러한 것이 학습에 대한 객관적인 판단 지표가 된다고 생각합니다.
- **획기적인 기술, 신기술을 무조건 따라가지 않습니다.** 세부적인 동작 원리와 구현 방식을 학습하고 상황과 시기에 따라 안정적으로 개발, 운영할 수 있는 기술을 선택하려고 노력합니다.
- **이해 당사자간의 토론과 지식 공유는 필수 불가결적인 요소라고 생각합니다.** 해당 도메인과 소프트웨어를 이해하지 못하는 개발팀에게는 한계가 있다고 생각합니다.
- **함께 자라는 것을 좋아하는 팀과 같이 일하고 싶습니다.** 이를 통해 앞으로 나아갈 동기를 얻을 수 있고, 활발한 토론과 피드백으로 성장해 나갈 수 있음을 믿습니다.

<br/>

## Backend Engineering.

- 현업을 포함 4개의 프로젝트 개발 경험
- Spring framework, JPA or Query 기반 Backend API 개발 경험

<br/>

## CI & CD & Devops.

- SFTP를 통한 수동 배포 방식에서 Jenkins의 Git Branch 연동을 이용한 자동화 배포 경험
- NCP Server와 AWS EC2 인스턴스 생성 및 WAS - DB 간의 연동 경험
- Docker를 통한 인스턴스 구성 *경험*

<br/>

## Database & SQL.

- MySQL과 MSSQL 사용 경험
- Flyway를 통한 Table Schema 버전 관리 경험

<br/>

## Testing.

- Junit을 이용한 테스트 작성 경험
- TestContainers를 통한 통합 테스트 환경 구성 및 테스트 경험

<br/>

## Tools & Work flow.

- Jira와 Confluence를 통한 스프린트, 작업 단위 관리, 진행 경험
- Git + Sourcetree를 사용한 Git-flow 사용 경험

<br/>

## Documentation.

- Swagger, Rest Docs를 이용한 API 문서화 경험

<br/>

# 👨🏻‍🎓 Education.

<br/>

## [IT 대기업 현업 개발자와 함께하는 백엔드 개발 실무 직무부트캠프](https://github.com/Lob-dev/Spring-WEB-API)

- **20.08.22 ~ 20.09.19**
    - RESTful 설계 방식의 SW 사용 통계 API 프로젝트
    - 협업을 위한 API의 가이드 문서를 작성하며 요청 파라미터 및 응답 데이터 포맷을 고려

<br/>

# 📚 Other Experience.

<br/>

## [TDD Study. DbUnit 발표](https://github.com/Lob-dev/Be-Docs-DbUnit)

- 2021.01
    - 데이터베이스 테스트와 하는 이유에 대해서 발표
    - 데이터베이스 테스트를 진행할 수 있는 DbUnit과 In-Memory 방식인 H2에 대해 발표
    - DbUnit을 사용하는 Test Code를 작성하는 Live Coding 진행

<br/>

## [Network Study. L4, L7, 보안 장비, 프록시 발표](https://www.notion.so/Network-3-535e95985ed5452797eabb31bad22476)

- 2021.03
    - L4와 L7 스위치의 개념과 지원 기능에 대해서 발표
    - 방화벽의 개념과 종류에 대해서 발표
    - 네트워크 프록시의 개념과 종류에 대해 발표
    - NAT에 대해서 발표

<br/>

## [JVM GC 기반 개념과 기본 GC 알고리즘](https://lob-dev.tistory.com/entry/Presentation-JVM-GC-%EA%B8%B0%EB%B3%B8-%EA%B0%9C%EB%85%90%EA%B3%BC-%EA%B8%B0%EB%B3%B8-GC-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98)

- 2021.04.27
    - 사내에서 JVM GC의 기본 개념인 Root Set, S-T-W, Reachability에 대해서 발표
    - Reference Counting 방식과 Tracing Garbage Collection 방식의 알고리즘에 대해 발표

<br/>

## [신입 개발자의 자바, 스프링 학습 자료](https://github.com/Lob-dev/Junior-Back-end-Developer-Concepts)

- 2021.04.29~(진행 중)
    - 오픈 커뮤니티에서 자바 기반의 Back-end 학습에 난항을 겪는 사람들을 도와주기 위해 만듦
    - 지속적인 개선, 업데이트를 진행

<br/>

## [JPA Basic Study](https://www.notion.so/JPA-Study-112458920130472894dc7955d8e1113d)

- **2021.05.22~(참여 중)**
    - Inflearn JPA 기본편 강의 내용을 바탕으로 한 주 학습 진도를 공부하고 리뷰 및 토론 진행

---
