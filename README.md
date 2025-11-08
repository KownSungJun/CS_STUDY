# CS_STUDY
https://velog.io/@prettylee620/CS-%EC%A7%80%EC%8B%9D-%EC%84%9C%EB%B2%84%EA%B4%80%EB%A0%A8
웹 cs 기본 지식을 정리할 repo
# index
1. [라이브러리, 프레임워크](#라이브러리-프레임워크)
2. API
3. [Server(Web Server, HTTP, 정적 웹 프로그래밍, 동적 웹 프로그래밍)](#server)
4. 싱글톤 디자인 패턴
5. 노출모듈 디자인 패턴
6. MVVM 디자인 패턴
7. 운영체제 Operation System
8. 메모리 관리
9. Call by value, Call by reference
10. String, StringBulider
11. 제네릭(Generics)

# 라이브러리 프레임워크

## 라이브러리

# API
# Server
- 컴퓨터의 서버는 클라이언트에 서비스를 제공한다
- 클라이언트로부터 `요청(request)`을 받아서 처음으로 처리를 시작하고, 서비스를 `제공, 응답(response)`한다

절차
1. 클라이언트는 서버에 무언가의 서비스를 요청한다
2. 서버는 요청에 따라 맞춰 처리를 수행한다
3. 서버는 처리 결과를 클라이언트로 반환시킴
4. 클라이언트는 처리 결과를 받음

## Web Server
- 하드웨어와 소프트웨어 혹은 두 개가 같이 동작하는 것을 의미
- 브라우저에서 웹 서버에 있는 파일이 필요할 때, 브라우저는 HTTP를 통해 파일을 요청
- 올바른 요청이 `웹 서버(하드웨어)`에 도달 시, `HTTP 서버(소프트웨어)`는 요청된 문서를 HTTP를 이용해 보내줌

## Web Server software 종류
- 서비스별로 서버 소프트웨어가 있으며, 각각의 특징은 있으나 웹 서버의 기능은 동일함
- Apache
- IIS
- nginx

## Web Container
- `서블릿 컨테이너`라고도 함
- JSP + Servlet을 실행시킬 수 있는 소프트웨어
- 웹 서버의 컴포넌트 중 하나로 자바 Servlet과 상호작용
- Servlet의 생명주기를 관리하고, URL과 특정 서블릿을 맵핑해 URL 요청이 올바른 접근 권한을 갖도록 보장함
- Servlet, 자바 서버 페이지
  
