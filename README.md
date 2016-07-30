publish.js

该文件是用来遍历src目录下所有的博客，截取该博客里的

```
---
title: 人生不能等待
categories: [心路历程]
date:2015-08-20
url:2015-08-20-do-not-wait
---
```

生成dist目录的ArticleList.json文件

```
{
    "articles": [
        {
            "title": "人生不能等待",
            "categories": "[心路历程]",
            "date": "2015-08-20",
            "url": "2015-08-20-do-not-wait"
        },
}
```