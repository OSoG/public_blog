---
layout: single
category: web
tags: [markdown]
---
무슨 일인지 아래 방법은 먹히지 않는다.
```
![My helpful screenshot](../assets/images/posts/2018-09-28-opencv/header2.jpeg)
```
대신, 아래 코드를 사용하였다.

```
![My helpful screenshot]({{"/assets/images/posts/2018-09-28-opencv/header2.jpeg" | absolute_url}})
```

![My helpful screenshot]({{"/assets/images/posts/2018-09-28-opencv/header2.jpeg" | absolute_url}})
