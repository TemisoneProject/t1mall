# t1mall [2023-11-24]
테미스원 쇼핑몰 프로젝트 (spring boot 3.2.0)

[2023-11-29]
 - 김태윤 : 깃 연동 테스트
 - 김정건 : 깃 연동 테스트
 - 장준환 : 깃 연동 테스트
 - 김지혜 : 깃 연동 테스트


[2023-12-11]
 - 장준환 : USER CRUD 브랜치 생성하기
[2023-12-13]
 - 장준환 : 프로젝트 구조 세팅 (develop 적용 2)



 [ERROR CODE]

 - Update your application to remove the dependency cycle between beans
 - 해당 메시지는 Spring Boot 2.6.x 버전부터, 순환 참조를 default로 금지함으로서 발생되는 에러메시지이다.
   -   main:
       allow-circular-references: true
   - application.yml에 위 구문을 추가함으로서 해결할 수 있다.