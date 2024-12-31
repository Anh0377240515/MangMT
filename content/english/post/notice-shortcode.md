+++
author = "Java Developers"
title = "Kế thừa trong Java"
date = "2024-12-30"
description = "Tìm hiểu về kế thừa trong Java và cách các lớp có thể mở rộng từ các lớp khác"
tags = [
    "java",
    "lập trình",
    "kế thừa",
]
+++

Kế thừa cho phép một lớp thừa hưởng các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.

```java
class Animal {
    void eat() {
        System.out.println("Con vật này ăn thức ăn.");
    }
}

class Dog extends Animal {
    void bark() {
        System.out.println("Con chó sủa.");
    }
}

public class InheritanceExample {
    public static void main(String[] args) {
        Dog dog = new Dog();
        dog.eat();  // Thừa hưởng từ lớp Animal
        dog.bark(); // Định nghĩa trong lớp Dog
    }
}
