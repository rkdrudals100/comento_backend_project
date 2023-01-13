> # comento_backend_project
 <br/>
코멘토 현업 개발자와 함께하는 백엔드 실무 과제 수행하기 프로젝트<br/><br/>

**목차**
- [1차 주간 보고](#1차-주간-보고)

<br/><br/><br/><br/>
> #1 차 주간 보고
<br/>

1.	Github 계정 생성
  1.1	과제를 수행하기 위한 Github 계정은 예전에 생성한 계정으로 사용하였습니다. 
  1.2	백엔드 개발 실무 프로젝트를 위한 리파지토리를 생성하였습니다.
  <br/><br/>
  
  
2.	JDK/Tomcat/mybatis Eclipse 설치
  2.1	JDK는 예전에 설치한 openjdk-8u292-b10 버전을 사용하였습니다.
  2.2	Eclipse는 2019-09 버전을 Tomcat은 9.0 버전을 설치하였습니다.
  2.3	이클립스 마켓플레이스에서 Spring Tools 3 (Standalone Edition) 3.9.12.RELEASE 설치 후 웹 프로젝트를 생성하였고 pom.xml에서 자바, 스프링 버전 등을 수정하였습니다.
  2.4	톰캣 9.0버전과 생성한 프로젝트를 연동해서 서버를 띄워보았습니다.
  <br/>
  
  ![image](https://user-images.githubusercontent.com/74872542/212350506-50a502bf-c009-4aad-9e70-b9c8f2d48abc.png)
  
  <br/>
  2.5	HomeController.java에 진입하면 아래의 에러가 발생하는데 아직 해결중입니다.
  <br/>
  
  ![image](https://user-images.githubusercontent.com/74872542/212350598-969d33a4-b318-4816-b10c-3906b8942576.png)
  
  <br/><br/>
3.	Mybatis 설치
  3.1 아직 설정하지 못했습니다.
 <br/><br/> 
  
  
4.	스프링 환경 구축 vs 스프링 부트 환경 구축 비교 해보기
  - 스프링 부트로 환경을 구축할 때는 Initializer을 통해서 최적화된 버전 설정, 의존성 설정, 내장 톰캣의 존재 등으로 초기 환경 구축에 큰 힘을 들이지 않았습니다.
  - 스프링으로 환경 구축을 할 땐 JDK, 스프링 버전, 이클립스 버전, 톰캣 버전 등 같이 사용할 수 있는 버전인지 확인을 해보고 직접 pom.xml을 수정해줘야 해서 스프링 부트에 비해 불편했습니다. 
  - 또한 스프링 부트와 다르게 필수 패키지를 자동으로 설치해주지 않아 필요하지만 설치가 안 되어있는 패키지(?) 때문에 Project Facets -> Dynamic Web Module 부분이 활성화되지 않았고 톰캣에 프로젝트를 적용시키지 못하는 문제가 있었습니다. 이 부분을 해결하는데 많은 시간을 사용하였습니다.


