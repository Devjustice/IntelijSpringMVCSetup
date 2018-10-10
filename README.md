# IntelijSpringMVCSetup
인텔리제이스프링설정파일
리눅스민트-MATE에 적합하게 톰켓서버 7버전과 연동함
사용 IDE:인텔리제이 Ultimate ver.
1.메이븐프로젝트생성
2.SpringMVC FrameWork추가
3.라이브러리다운로드
4.web.xml수정
<servlet-name>dispatcher</servlet-name>
        <url-pattern>/</url-pattern> <!-- *.form -> / 바꾸기-->
5.Artifacts 라이버러리 추가
6.dispatcher-servlet.xml annotation활성화 & component-scan 파일지정
7.views디렉터리생성 & index.jsp이동시키기
8.Controller디렉터리생성 & controller code 작성
9.Run Edit Conf로 Tomcat Server 추가하기
10.WEB-INF 경로설정
11.Open Module Setting 경로 Web Resource Directory web으로 수정
12.Artifacts Library추가
13. 서버 Run 후 LocalHost:8080확인
참고 https://nesoy.github.io/articles/2017-02/SpringMVC
