# 论文列表

导航栏 Publications 页面（_pages/publications.html）会自动列出本文件夹下的所有条目，一篇文章一个 .md 文件。

## 添加一篇论文

新建文件 `YYYY-MM-DD-简短标题.md`（日期填发表时间），套用下面的模板：

```yaml
---
title: "论文标题"
collection: publications
category: manuscripts    # manuscripts=期刊论文 / conferences=会议论文 / books=专著
permalink: /publication/YYYY-MM-DD-简短标题
excerpt: "一句话摘要"
date: YYYY-MM-DD
venue: "期刊或会议名称"
paperurl: "https://yaoweiwei-1005.github.io/files/paper1.pdf"
citation: "Wang, R. (2026). &quot;论文标题.&quot; <i>期刊名</i>."
---
这里写论文详情页的正文，没有就留空
```

- PDF 放到根目录的 `files/` 文件夹（没有就新建），`paperurl` 填它的网址
- 分组标题（Journal Articles / Conference Papers 等）在 `_config.yml` 的 `publication_category` 里改
