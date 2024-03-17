# 이 프로젝트를 만든 이유

예전에 짰던 Spring boot 프로젝트들을 실행 시킬 수 없어서, 예전에 뭘 했었는지 정리도 하고 좀 더 portable 하게 만들기 위해 시작
https://start.spring.io/ 에서 다음을 선택
- Gradle - Groovy
- Java
- 3.2.3
- Jar
- 17



## 커멘드라인으로 프로젝트 빌드 실행
```
./gradlew --refresh-dependencies
./gradlew build 빌드하기
./gradlew bootRun 실행하기
./gradlew jar
```