---
title: "Quản lý bộ nhớ trong Java và JavaScript"
date: 2025-10-01
slug: /quan-ly-bo-nho/
description: So sánh cơ chế quản lý bộ nhớ của Java và JavaScript, cách hoạt động của Garbage Collector.
image: images/memoryjavascript.jpg
caption: Bộ nhớ trong lập trình
draft: false
tags: ["Java", "JavaScript", "Lập trình"]
categories: ["Lập trình"]
---

## Java
- Quản lý bộ nhớ qua JVM.  
- Có Heap, Stack.  
- Garbage Collector tự động dọn dẹp.  

Ví dụ:

```java
String s = new String("Hello");
```

## JavaScript

* Quản lý qua cơ chế Mark-and-Sweep.
* Tự động loại bỏ biến không còn tham chiếu.

Ví dụ:

```javascript
let a = {name: "Minh"};
a = null; // biến sẽ được dọn dẹp
```

**Lưu ý để tránh Memory Leak**

* Không giữ tham chiếu không cần thiết.
* Hạn chế global variables.

## Kết luận

Cả Java và JS đều giúp lập trình viên không phải quản lý bộ nhớ thủ công, nhưng cần viết code cẩn thận để tránh rò rỉ.