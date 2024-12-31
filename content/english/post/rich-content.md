+++
author = "Java Developers"
title = "Xử lý ngoại lệ trong Java"
date = "2024-12-30"
description = "Tìm hiểu cách xử lý ngoại lệ trong Java bằng các khối try-catch"
tags = [
    "java",
    "lập trình",
    "xử lý ngoại lệ",
]
+++

Java cung cấp một cơ chế xử lý ngoại lệ mạnh mẽ bằng cách sử dụng các khối `try`, `catch` và `finally` để xử lý các lỗi xảy ra khi chạy chương trình.

```java
public class ExceptionHandling {
    public static void main(String[] args) {
        try {
            int result = 10 / 0;
        } catch (ArithmeticException e) {
            System.out.println("Lỗi: Chia cho số 0");
        } finally {
            System.out.println("Khối này luôn được thực thi");
        }
    }
}
