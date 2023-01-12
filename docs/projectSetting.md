# [inflearn] Spring 입문 - 실습

## Spring initializr

프로젝트 생성 : [spring initializr](https://start.spring.io)

- Project `Gradle - Groovy`
- Language `Java`
- Spring Boot `3.0.1`
- Packaging `Jar`
- Java `17`
- Dependencies
  + Spring Web
  + Thymeleaf


## IntelliJ setting
- Preferences > Build, Excution, Deployment > Build Tools > Gradle
  + Gradle JVM: JDK 17


- Application 실행 시 아래와 같은 경고 문구 표시되는 경우 세팅
  > OpenJDK 64-Bit Server VM warning: Options -Xverify:none and -noverify were deprecated in JDK 13 and will likely be removed in a future release
  + Application Run Configuration > Build and run > Modify options > Disable launch optimization


- Application 실행 느린 경우 아래와 같이 설정하면 속도 개선됨
  + Preferences > Build, Excution, Deployment > Build Tools > Gradle
    - Build and run using : IntelliJ IDEA
    - Run tests using : IntelliJ IDEA