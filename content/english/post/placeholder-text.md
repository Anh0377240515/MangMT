+++
author = "Java Developers"
title = "Tính đa hình trong Java"
date = "2024-12-30"
description = "Tìm hiểu cách tính đa hình hoạt động trong Java, cho phép một giao diện được sử dụng cho nhiều loại đối tượng khác nhau"
tags = [
    "java",
    "lập trình",
    "đa hình",
]
+++

Tính đa hình cho phép các đối tượng thuộc các lớp khác nhau được xử lý như các đối tượng của một lớp cha chung. Nó hỗ trợ ghi đè phương thức và nạp chồng phương thức.

```java
class Animal {
    void sound() {
        System.out.println("Con vật phát ra âm thanh");
    }
}

class Dog extends Animal {
    void sound() {
        System.out.println("Con chó sủa");
    }
}

class Cat extends Animal {
    void sound() {
        System.out.println("Con mèo kêu meo meo");
    }
}

public class PolymorphismExample {
    public static void main(String[] args) {
        Animal myAnimal = new Animal();
        Animal myDog = new Dog();
        Animal myCat = new Cat();

        myAnimal.sound
