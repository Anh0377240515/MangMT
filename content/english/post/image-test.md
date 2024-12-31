+++
author = "Java Developers"
title = "Câu lệnh điều khiển trong Java"
date = "2024-12-30"
description = "Tìm hiểu các câu lệnh điều khiển như if, else, for, while trong Java"
tags = [
    "java",
    "lập trình",
    "câu lệnh điều khiển",
]
+++

Các câu lệnh điều khiển trong Java như `if`, `else`, `switch`, `for`, `while`, và `do-while` được sử dụng để điều khiển luồng thực thi của chương trình.

```java
public class ControlFlow {
    public static void main(String[] args) {
        int number = 20;
        if (number > 10) {
            System.out.println("Số lớn hơn 10");
        } else {
            System.out.println("Số nhỏ hơn hoặc bằng 10");
        }
    }
}
