---
title: "Bất đồng bộ trong JavaScript – Callback, Promise, Async/Await"
date: 2025-10-01
slug: /javascript-bat-dong-bo/
description: Tìm hiểu mô hình bất đồng bộ trong JavaScript, từ Callback đến Promise và Async/Await.
image: images/javascript-batdongbo.jpg
caption: Xử lý bất đồng bộ trong JS
draft: false
tags: ["JavaScript", "Async", "Promise", "Lập trình"]
categories: ["Lập trình"]
---

## Callback
```javascript
setTimeout(() => {
  console.log("Xin chào sau 2 giây!");
}, 2000);
```

## Promise
```javascript
let promise = new Promise((resolve, reject) => {
  resolve("Thành công!");
});

promise.then(msg => console.log(msg));
```

## Async/Await
```javascript
async function hello() {
  return "Xin chào!";
}

hello().then(msg => console.log(msg));
```

## Kết luận

Từ Callback đến Async/Await, JS đã ngày càng dễ dàng hơn trong xử lý bất đồng bộ.