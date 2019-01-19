---
layout: post
title: "syntax test"
description: "test"
date: 2019-01-17
tags: [syntax]
category: Mathematics
comments: true
share: true
---

```python
import tensorflow as tf

a = tf.constant([[1., 2.], [3., 4.]]) # 2x2 행렬
b = tf.constant([[5.], [6.]]) # 2x1 행렬
y = tf.matmul(a, b)

sess = tf.Session()
print(sess.run(y))
```