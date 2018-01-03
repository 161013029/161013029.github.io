---
layout: archive
title: "ROLE 角色"
date: 2017-12-30T11:40:45-04:00
modified:
excerpt: "LINE FRIENDS中的重要角色"
tags: []
image: 
  feature: Portfolio.svg
  teaser:
---
- 个性温和 呆萌老实的BROWN 布朗熊。
- 活泼开朗的CONY 可妮兔
- 一无所知 单纯又性急的SALLY 莎莉鸡
- 严重自恋狂的JAMES 詹姆斯


<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 portfolio 的列出來-->
