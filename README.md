<h1>팀프로젝트
프로젝트명: Local Travel</h1>

<h3>개발기간</h3>
2.11 ~ 2.22

<h3>개발 목표</h3>
JSP, 서블릿을 이용하여 특색 있는 여행지의 정보들을 검색하고 스크랩하여 개인이 여행정보를 얻는 데 도움을 줄수 있는 여행정보 사이트 개발

<h3>개발 환경</h3>
운영체제- Window10

사용 언어- Java, Javascript, Html, css

라이브러리, 프레임워크- Jquery, Bootstrap

IDE- 이클립스

<h3>DB설계</h3>
<img width="889" alt="default" src="https://user-images.githubusercontent.com/36668707/65382850-00a97480-dd48-11e9-8954-add13676b188.png">


<h3>구현기능</h3>
<h3>JDBC 템플릿을 이용한 DB 연동</h3>
DBMS 연동, 객체반환, 트렌젝션 처리 등 중복 코드를 새로운 클래스에서 구동될 수 있게 연동 재설계
Connection 생성, Connection/Statement/PreparedStatement 반환 메소드, 
트렌젝션(commit. rollback)
<img width="500" alt="default" src="https://user-images.githubusercontent.com/36668707/65382990-3e5acd00-dd49-11e9-82a2-b6d56443b2cf.png">
<img width="450" alt="default" src="https://user-images.githubusercontent.com/36668707/65383001-7104c580-dd49-11e9-8ed4-3334973c8e94.png">


<hr>
<h3>Ajax 이용한 스크랩</h3>
로그인하지 않은 상태에서
스크랩하기 버튼을 누르면 
스크랩할 수 없고, 
로그인한 후에 스크랩하기 버튼을 클릭하면 스크랩을 할 수 있다.
<img width="600" alt="default" src="https://user-images.githubusercontent.com/36668707/65383074-7a426200-dd4a-11e9-96fb-2cbe5287c6c8.png">


<hr>
<h3>비밀번호 암호화</h3>
로그인할 때 아이디와 
비밀번호를 입력하는데
이때 비밀번호는 로그인 버튼을 눌렀을 때 서블릿을 통해 데이터베이스로 전송된다.
이때 SHA 512 암호화 
메소드가 작동하여 암호화된 
상태로 데이터베이스에 
저장된다.
<img width="500" alt="default" src="https://user-images.githubusercontent.com/36668707/65383097-defdbc80-dd4a-11e9-867f-3a951b3e4603.png">
<img width="500" alt="default" src="https://user-images.githubusercontent.com/36668707/65383111-1a988680-dd4b-11e9-9e54-452ed029ed54.png">

<hr>
<h3>개선사항</h3>
1 코드 리팩토링
<br>
2 인터페이스 사용하여 클래스간 의존성 낮추기

3 테스트 코드 추가
