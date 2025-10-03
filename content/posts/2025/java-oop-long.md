---
title: "Lập trình Hướng Đối Tượng trong Java – Hành trình từ cơ bản đến nâng cao"
date: 2025-10-01
slug: /java-oop-hanh-trinh/
description: Tìm hiểu chi tiết về lập trình hướng đối tượng (OOP) trong Java với 4 nguyên lý cơ bản
image: images/javaoop.jpg
caption: Photo by 
draft: false
tags: ["Java", "OOP", "Lập trình"]
categories: ["Lập trình"]
---

Trong bài viết này, chúng ta sẽ tìm hiểu chi tiết về **Lập trình Hướng Đối Tượng (OOP)** trong Java. Đây là một trong những khái niệm quan trọng nhất giúp Java trở thành ngôn ngữ mạnh mẽ và phổ biến.

---

## OOP là gì?

OOP (Object-Oriented Programming) là mô hình lập trình dựa trên **đối tượng**. Thay vì chỉ dùng hàm và dữ liệu, chúng ta mô hình hóa mọi thứ thành đối tượng có **thuộc tính** và **hành vi**.

Ví dụ trong Java:

```java
class Student {
    String name;
    int age;

    void study() {
        System.out.println(name + " đang học...");
    }
}
```

## 4 nguyên lý của OOP
**Encapsulation (Đóng gói)**

Giúp bảo vệ dữ liệu, chỉ cho phép truy cập thông qua phương thức.

Ví dụ:

```java
class BankAccount {
    private double balance;

    public void deposit(double amount) {
        balance += amount;
    }

    public double getBalance() {
        return balance;
    }
}
```

**Inheritance (Kế thừa)**

Cho phép lớp con kế thừa thuộc tính và phương thức từ lớp cha.

Ví dụ:
```java
class Animal {
    void sound() {
        System.out.println("Some sound...");
    }
}

class Dog extends Animal {
    void sound() {
        System.out.println("Woof woof!");
    }
}
```

**Polymorphism (Đa hình)**

Một phương thức có thể có nhiều cách triển khai.

Ví dụ:
```java
Animal a = new Dog();
a.sound(); // Kết quả: Woof woof!
```

**Abstraction (Trừu tượng)**

Che giấu chi tiết, chỉ cho thấy cái cần thiết.

Ví dụ:
```java
abstract class Shape {
    abstract void draw();
}

class Circle extends Shape {
    void draw() {
        System.out.println("Vẽ hình tròn");
    }
}
```

## Ứng dụng thực tế của OOP
**Phát triển phần mềm lớn:** dễ bảo trì, mở rộng.

**Lập trình Android:** Java là ngôn ngữ chính trước đây.

**Hệ thống doanh nghiệp:** ERP, CRM đều áp dụng OOP.

## Kết luận

OOP là nền tảng giúp bạn trở thành lập trình viên Java giỏi.
Hãy luyện tập thật nhiều bằng cách viết các lớp, kế thừa và áp dụng 4 nguyên lý trên.
```
“Hiểu OOP là bạn đã đi được nửa chặng đường học Java.”
```