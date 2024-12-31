+++
author = "Java Developers"
title = "Lớp và Đối tượng trong Java"
date = "2024-12-30"
description = "Tìm hiểu về lớp và đối tượng trong Java, những khái niệm cơ bản của lập trình hướng đối tượng"
tags = [
    "java",
    "lập trình",
    "lớp",
    "đối tượng",
]
+++

Java là một ngôn ngữ lập trình hướng đối tượng. Bạn có thể tạo lớp để định nghĩa các đối tượng với thuộc tính và phương thức.

```java
public class Car {
    String model;
    int year;

    public void start() {
        System.out.println("Xe đang khởi động...");
    }

    public static void main(String[] args) {
        Car myCar = new Car();
        myCar.model = "Toyota";
        myCar.year = 2022;
        myCar.start();
    }
}
