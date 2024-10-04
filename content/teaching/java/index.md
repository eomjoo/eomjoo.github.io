---
title: Learn Java
summary: Easily learn Java in 10 minutes!
date: 2023-10-24
type: docs
featured: true
math: false
tags:
  - Java
image:
  caption: 'Java'
  filename: 'Java.jpg'
  focal_point: 'center'
  preview_only: false
  style: "object-fit: contain; width: 100%;"  # 이미지 비율과 크기 조정
---

Java는 플랫폼에 독립적인 객체 지향 프로그래밍 언어로, 다양한 응용 프로그램을 개발하는 데 널리 사용됩니다. 이 섹션에서는 Java의 기본 문법, 언어의 주요 특징, 그리고 응용 기술에 대해 알아보겠습니다.

## Java의 특징
- **객체 지향 언어:** Java는 객체 지향 프로그래밍(OOP) 개념을 기반으로 설계되어 유지보수가 쉽고 재사용성이 높은 코드를 작성할 수 있습니다.
- **플랫폼 독립성:** Java로 작성된 프로그램은 Java Virtual Machine(JVM)에서 실행되기 때문에 운영체제에 상관없이 실행 가능합니다.
- **메모리 관리:** Java는 가비지 컬렉션(Garbage Collection)을 통해 자동으로 메모리를 관리합니다.
- **보안:** Java는 다양한 보안 기능을 제공하여 안전한 애플리케이션을 개발할 수 있도록 지원합니다.
- **다양한 라이브러리:** Java에는 광범위한 라이브러리와 프레임워크가 있어 개발 생산성을 높여줍니다.

## 기초 문법
### 1. Hello World
Java의 기본적인 프로그램 구조는 다음과 같습니다. Java 프로그램은 클래스 내의 `main` 메서드로부터 실행이 시작됩니다.

```java
public class Main {
    public static void main(String[] args) {
        // Java의 특징
        System.out.println("Java의 특징:");
        System.out.println("- 객체 지향 언어: 유지보수와 재사용성에 용이한 구조 설계 가능");
        System.out.println("- 플랫폼 독립성: JVM으로 어느 운영체제에서도 실행 가능");
        System.out.println("- 메모리 관리: 가비지 컬렉션을 통해 자동으로 메모리 관리");
        System.out.println("- 보안: 다양한 보안 기능 제공");
        System.out.println("- 다양한 라이브러리: 광범위한 라이브러리와 프레임워크 지원");

        // 변수와 데이터 타입
        System.out.println("\n기초 문법 예제:");
        int number = 10;        // 정수형
        double price = 19.99;   // 실수형
        char letter = 'A';      // 문자형
        boolean isJavaFun = true; // 불린형
        String text = "Java Programming"; // 문자열

        System.out.println("정수형 변수: " + number);
        System.out.println("실수형 변수: " + price);
        System.out.println("문자형 변수: " + letter);
        System.out.println("불린형 변수: " + isJavaFun);
        System.out.println("문자열 변수: " + text);

        // 조건문 예제
        System.out.println("\n조건문 예제:");
        if (number > 0) {
            System.out.println("number는 양수입니다.");
        } else {
            System.out.println("number는 음수입니다.");
        }

        // 반복문 예제
        System.out.println("\n반복문 예제 (0부터 4까지 출력):");
        for (int i = 0; i < 5; i++) {
            System.out.println("Count: " + i);
        }

        // 응용 기술 소개
        System.out.println("\nJava 응용 기술:");
        System.out.println("- Java SE: 기본 라이브러리 및 API를 제공하는 표준 버전");
        System.out.println("- Java EE: 엔터프라이즈 애플리케이션 개발을 위한 다양한 API와 프레임워크 포함");
        System.out.println("- Java ME: 모바일 및 임베디드 기기용 경량 버전");
        System.out.println("- Spring Framework: 가장 널리 사용되는 엔터프라이즈급 애플리케이션 프레임워크");
        System.out.println("- Hibernate: 데이터베이스 상호작용을 위한 ORM 프레임워크");
        System.out.println("- Apache Maven/Gradle: Java 프로젝트의 빌드와 의존성 관리 도구");
    }
}
