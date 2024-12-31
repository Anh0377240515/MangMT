+++
author = "Java Developers"
title = "Phương thức trong Java"
date = "2024-12-30"
description = "Tìm hiểu cách định nghĩa và gọi phương thức trong Java"
tags = [
    "java",
    "lập trình",
    "phương thức",
]
+++

Trong Java, phương thức cho phép bạn tổ chức mã thành các khối tái sử dụng. Bạn có thể định nghĩa các phương thức với tham số và kiểu trả về.

```java
public class MethodsExample {
    public static void main(String[] args) {
        int sum = addNumbers(5, 10);
        System.out.println("Tổng: " + sum);
    }

    public static int addNumbers(int a, int b) {
        return a + b;
    }
}
