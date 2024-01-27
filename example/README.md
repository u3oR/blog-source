# POST

所有的文章头部都有一段`json`，它描述了该文章的一些信息。

```json
{
    "front-matter": {
        "title": "文章の标题",
        "date": "2023-08-29",
        "author": "我是谁",
        "tags": ["Example1", "Example1"],
        "categories": "Cate",
        "description": "文章描述",
        "cover": "封面图片链接",
        "featured": false, 
        "draft": true 
	}
}
```

.

| 变量            | 说明          |
| --------------- | ------------- |
| `"title"`       | 文章名字      |
| `"date"`        | 文章日期      |
| `"author"`      | 文章作者      |
| `"tags"`        | 文章标签      |
| `"categories"`  | 文章分类      |
| `"description"` | 文章描述      |
| `"cover"`       | 封面图片链接  |
| `"featured"`    | 🟡             |
| `"draft"`       | 是否 是草稿？ |

完。
