# spring_introduction
	스프링 입문 - 코드로 배우는 스프링 부트, 웹 MVC, DB 접근 기술

## 라이브러리 살펴보기👌

Gradle은 의존관계가 있는 라이브러리를 함께 다운로드 한다.

"스프링 부트 라이브러리"
- spring-boor-starter-web
-> spring-boot-stater-tomcat : 톰캣(웹서버)
-> spring-webmvc : 스프링 웹 MVC

- spring-boot-starter-thymeleaf : 타임리프 템플릿 엔진(View)
- spring-boot-stater(공통) : 스프링 부트 + 스프링 코어 + 로깅
	-	spring-boot
	-	spring-core
- spring-boot-starter-logging
	- logback, slf4j

"테스트 라이브러리"
- spring-boot-starter-test
	- junit : 테스트 프레임워크
	- mockito : 목 라이브러리
	- assertj : 테스트 코드를 좀 더 편하게 작성하게 도와주는 라이브러리
	- spring-test : 스프링 통합 테스트 지원