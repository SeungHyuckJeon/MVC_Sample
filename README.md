# MVC_sample
jsp's MVC Sample Project


# Source Files Path
## Java files
/src/Tablename/tablenameDAO(DTO).java

## JSP
/WebContents/pageType/pageName.jsp

## JavaScript
- 웬만하면 작동되는 페이지내에 script 태그로 묶어서 사용하기
- 만약 여러 페이지에서 공통적으로 사용하는 function들은 /WebContent/Common/JS 폴더에서 js파일 만들어 사용

## DB 연동 방법

1. DBCP(Database Connection Pool)

   1. JNDI

      - **Server/server.xml과 Server/context.xml 에서 연결**

      - 프로젝트/WebContent/WEB-INF/web.xml 에서 연결

2. JDBC