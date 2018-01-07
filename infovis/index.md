---
layout: archive
title: "可视化作品集"
date: 2017-12-30T11:40:45-04:00
excerpt: "我的可视化作品"
---
## 我国国产手机专卖店对比简要分析(数据来源：高德地图)
<a href="https://public.tableau.com/profile/.81587557#!/vizhome/_18192/1_2?:embed=y&:display_count=yes&publish=yesDashboard1?:showVizHome=no&:embed=true" target="_blank"><img src="/images/yibiaopan.jpg" width="670" height="550" border="0" /></a>
   
## 我的所有可视化作品集
<div class="tiles">
{% for post in site.categories.vzuo %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 vzuo 的列出来-->
