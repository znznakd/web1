# 📘 Spring & Java 프로젝트 정리

이 저장소는 **Spring Framework**와 **Java**를 활용한 백엔드 개발 학습 및 실습 내용을 정리한 공간입니다. 주요 개념, 실습 코드, 예제 프로젝트 등을 담고 있으며, Spring 기반 백엔드 개발자로 성장하기 위한 내용을 단계별로 구성했습니다.

---

## 📌 목차

1. [Spring Framework 개요](#spring-framework-개요)  
2. [주요 학습 내용](#주요-학습-내용)  
3. [실습 예제 소개](#실습-예제-소개)  
4. [실행 방법](#실행-방법)  
5. [기타 참고자료](#기타-참고자료)

---

## 🧭 Spring Framework 개요

Spring Framework는 **자바 기반의 오픈소스 애플리케이션 프레임워크**로, **경량화된 DI/IoC 컨테이너**를 중심으로 다양한 컴포넌트를 제공합니다. 실무에서 널리 사용되는 웹 백엔드 기술로, 생산성과 유지보수 측면에서 강력한 장점을 가지고 있습니다.

---

## 🔍 주요 학습 내용

- Java 기반 프로젝트 구조 이해  
- MVC 패턴과 계층형 아키텍처 구성  
- IoC/DI (제어의 역전 / 의존성 주입)  
- Spring Boot를 활용한 빠른 서버 구축  
- Controller, Service, Repository의 역할  
- JPA & MyBatis 등 ORM 사용 방법  
- 데이터베이스 연동 및 CRUD 구현  
- RESTful API 설계 및 예외 처리  
- Validation과 사용자 입력 검증  
- 간단한 게시판 프로젝트 구현  

---

## 💻 실습 예제 소개

| 예제 명 | 내용 | 주요 기술 |
|--------|------|-----------|
| 회원 관리 | 회원가입, 로그인, 회원 정보 조회 등 | Spring MVC, MyBatis |
| 게시판 구현 | 게시글 작성, 조회, 수정, 삭제 | JPA, Thymeleaf |
| REST API 서버 | JSON 기반의 API 응답 처리 | Spring Boot, REST, Postman |
| DB 연동 | Oracle/MySQL과의 연결 및 CRUD 처리 | JDBC, Spring Data JPA |

---

## 🛠 실행 방법

1. **JDK 설치 (Java 11 이상)**
2. **IDE (IntelliJ 또는 Eclipse) 준비**
3. **데이터베이스 설정**
    - `application.properties` 혹은 `application.yml` 파일에 DB 정보 입력
4. **프로젝트 빌드**

    ```bash
    ./gradlew build
    ```

5. **애플리케이션 실행**

    ```bash
    ./gradlew bootRun
    ```

---

## 🔗 기타 참고자료

- [Spring 공식 문서](https://spring.io/projects/spring-framework)  
- [Baeldung - Spring 가이드](https://www.baeldung.com/)  
- [스프링 입문 강의 (김영한)](https://www.inflearn.com/course/스프링-입문)

---

## ⚙️ 기술 스택

- Java 11  
- Spring Boot 2.x  
- MyBatis / JPA  
- Oracle / MySQL  
- Gradle / Maven  
