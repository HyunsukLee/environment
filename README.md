	3.0 개발 환경 준비
	개발 환경 준비
	spring tool suite 3.9.8
	sourcetree 2.6.10
	apache-gradle
	jdk 1.8.x
	redis
	
	프레임워크
	Spring boot 2.1.1 (2.1이상 사용)
check 	spring framework 5.0.9.RELEASE
	embedded tomcat 8.5.34(scope:provided)
	jackson 2.9.6
check 	spring data redis
check 	spring test(scope:test)
	lombok 1.18.6
check 	lettuce-5.0.5.RELEASE
	mybatis 1.3.2
	spring rest doc
check 	mapstruct 1.3.0.Final
	logback
check 	connection pool
	junit
	git
	jenkins (우선순위 낮음)
	nexus (우선순위 낮음)
front 확인	graphQL (검토중) sample 개발필요
	
	실행
	openjdk (version : 8.0.202.08) 설치
	sourcetree (version : 2.6.10) 설치
	spring tool suite (version : 3.9.8) 설치
	
	기타 실행
	
	
	개발
	개발프로세스
	
	배포프로세스
	개발
	운영
	
	소스 버전 관리
	해당 브랜치 구조는 git-flow 정책을 따름
	브랜치 구조
	local - dev - QC - stage - master(LIVE)
	
	
	
	
	
	
	디렉토리 구조
	기본 패키지 구성은 maven package 기준을 따른다
	/src/main/java : 공통, 비지니스 로직를 모두 포함하는 영역
	/src/main/resource : 외부 설정 영역
	/src/test/java : 테스트 영역
	
	ex. 대상 : com.cyworld.thenew.controller.PostController  테스트케이스 : com.cyworld.thenew.controller.PostTest
	
	
	
	기존 소스 분석
	회원
	홈서비스
	뮤직, 클럽, 선물가게
	신규 설계
	회원
	포스팅
	방명록
	타임라인
	미니미, 미니룸
	선물가게 (빌링)
	보상
	지갑
	클럽
	배치
	통계
	어드민
