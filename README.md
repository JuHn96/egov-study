# eGovFrame Study

전자정부 표준프레임워크(eGovFrame)를 단순히 따라 하는 것이 아니라,
Java, Spring, Web, DB, Docker 등 기반 원리부터 이해하며 학습하는 저장소입니다.

## 학습 목표

- Linux / WSL 기반 개발환경 구성
- Git / GitHub 활용
- Docker / Docker Compose 이해 및 운영
- 웹 애플리케이션 동작 원리 이해
- Java 핵심 이해
- Spring / Spring MVC 이해
- DB / MyBatis 이해
- JSP 이해
- eGovFrame 구조 이해
- CRUD 직접 개발
- 기존 공공기관 eGovFrame 프로젝트 분석 및 수정
- 최종 Main Project 완성

## 학습 목차

- Chapter 0. 개발환경 및 프로젝트 구축
- Chapter 1. 웹 애플리케이션 동작 원리
- Chapter 2. eGovFrame에 필요한 Java 핵심
- Chapter 3. Spring 핵심 원리
- Chapter 4. Spring MVC와 요청 처리
- Chapter 5. DB와 MyBatis
- Chapter 6. JSP와 화면 처리
- Chapter 7. 전자정부 표준프레임워크
- Chapter 8. eGovFrame CRUD 프로젝트
- Chapter 9. 공공기관 실무 프로젝트 분석

## 현재 진도

- [x] Chapter 0-1. WSL / Linux 기본 구조
- [x] Chapter 0-2. Ubuntu 패키지 관리와 APT
- [ ] Chapter 0-3. JDK와 Maven 개발도구 구성

## Repository 구조

```text
egov-study/
├── README.md
├── docs/
├── labs/
├── main-project/
└── troubleshooting/
```

## Study Log

### 2026-09-24

- Ubuntu 26.04 WSL 학습환경 확인
- OpenJDK 21 설치
- Apache Maven 3.9.12 설치
- `java`, `javac`, `mvn` 실행 경로 확인
- `PATH`, `JAVA_HOME`, `update-alternatives` 관계 확인
- `Hello.java` 직접 작성
- `javac`로 Java 소스 코드를 `.class` Bytecode로 컴파일
- `java Hello`로 JVM 실행 확인
- `javap -c`로 Bytecode 확인
- `.gitignore`에 `*.class`를 등록해 컴파일 결과물 제외
- `JAVA_HOME`을 `~/.bashrc`에 설정
- GitHub Repository를 WSL 환경에 clone하고 VS Code와 연결