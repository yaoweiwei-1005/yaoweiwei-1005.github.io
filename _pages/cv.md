---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Cyber Science and Technology, Shandong University, 2026–2029 (expected)
  * School of Cyber Science and Technology, Qingdao
  * Advisor: Prof. [Shiyao Chen](https://faculty.sdu.edu.cn/chenshiyao/zh_CN/index.htm), Symmetric Cryptography Group
<!-- 本科信息补充在这里，例如：
* B.S. in XXX, XXX University, 2022–2026
-->

Research Interests
======
* Symmetric cryptography
* Block ciphers: security analysis and design

<!-- Skills / Awards / Experience 等栏目需要时再添加 -->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
