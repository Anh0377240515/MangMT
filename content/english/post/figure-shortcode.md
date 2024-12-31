+++
author = "Java Developers"
title = "Các kiểu dữ liệu trong Java"
date = "2024-12-30"
description = "Tìm hiểu về các kiểu dữ liệu trong Java"
tags = [
    "java",
    "lập trình",
    "kiểu dữ liệu",
]
+++

Java cung cấp một số kiểu dữ liệu cơ bản như `int`, `double`, `boolean`, `char`, v.v. Các kiểu dữ liệu này được sử dụng để khai báo biến và thực hiện các phép toán.

```java
public class DataTypes {
    public static void main(String[] args) {
        int number = 10;
        double pi = 3.14;
        boolean isJavaFun = true;
        char grade = 'A';

        System.out.println("Số: " + number);
        System.out.println("Số Pi: " + pi);
        System.out.println("Java có thú vị không? " + isJavaFun);
        System.out.println("Xếp hạng: " + grade);
    }
}
