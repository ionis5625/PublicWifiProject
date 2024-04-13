# Public Wifi Project
- 목표 : 서울시에서 제공하는 공공 API를 이용해 자신의 위치에서 가장 가까운 공공와이파이의 개수를 20개까지 출력한다. 그리고 그 와이파이에 대한 북마크 기능도 제공할 수 있도록 한다.

### 사용 언어 및 툴(필수 준수 사항)
Java, Maven, SQLite(+ERD 작성을 위한 MySQL 활용), DBeaver, Tomcat, Lombok, Okhttp3, Gson

### 작업 순서
1. 공공데이터 포탈 회원가입 및 사용하고자 하는 API 검색
2. 공공데이터 포탈에서 오픈API 데이터 확인 및 API 요청을 통한 결과 확인
3. API요청을 JAVA로 호출 및 결과 내용 테스트(WebRequest Util이용)
4. 이클립스 or 인텔리제이를 통해서 다이나믹 웹 프로젝트 생성 후 페이지(JSP) 구성
5. ERD를 통한 데이터 모델링 진행
6. 데이터베이스 구성 및 연결 테스트 진행(DB툴 을 이용하여)
7. 데이터베이스에 테이블 생성
8. JAVA를 통한 SQLite 데이터베이스 연동 테스트 진행
9. JSP를 통한 목록 조회에 대한 SQL작성 및 연동 작업 진행
10. 페이지 작성

### 과제를 진행하며 어려웠던 점
코드를 짜는 것 자체는 검색과 템플릿을 사용하여 수월하게 진행하였으나 중간에 생각지도 못한 오류가 상당히 많았다. 
가장 해결하기 힘들었던 서버 리퀘스트 오류도 있었고 의존성 주입이 원활하게 되지 않아 코드를 다시 작성하는 경우도 있었다. 
다음부턴 중간중간 테스트를 진행하며 오류를 수정하는게 더 나을 것 같다.