---
layout: archive
title: "WEB作品集"
date: 2017-12-30T11:40:45-04:00
modified:
excerpt: "我的WEB作品"
tags: []

---

<!doctype html>
<html class="no-js" lang="zh-CN">
	<head>
		<meta charset="utf-8">
		<title>LINE FRIENDS</title>
		<meta name="description" content="LINE FRIENDS 为什么这么火">
		<meta name="viewport" content="width=device-width">
		<link rel="stylesheet" href="css/styles.css">
	</head>
	<body>
		<div class="Header">
			<a href="/" class="LogoWrapper"><img src="http://7xo6kd.com1.z0.glb.clouddn.com/upload-ueditor-image-20170913-1505316242901053913.jpg" title="http://7xo6kd.com1.z0.glb.clouddn.com/upload-ueditor-image-20170913-1505316242901053913.jpg" alt="timg (1).jpg"/></a>
			<p class="Strap">LINE FRIENDS:打造品牌</p>
		</div>
		<div class="IntroWrapper">
			<p class="IntroText">朝着社交元素不断发展的LINE，越来越像年轻人生活的style，而不仅是一款通讯工具。
				<!-- 根據 https://www.bilibili.com/video/av6713857/  -->
+				<embed height="452" width="544" quality="high" allowfullscreen="true" type="application/x-shockwave-flash" src="https://static-s.bilibili.com/miniloader.swf" flashvars="aid=6713857&page=1" pluginspage="http://www.adobe.com/shockwave/download/download.cgi?P1_Prod_Version=ShockwaveFlash"></embed>
		        </p>
			<div class="MoneyShot">
				<a herf="http://www.un.org/sustainabledevelopment/zh/sdgadvocates" />
				<img class="MoneyShotImg" width="100%" <img src="http://7xo6kd.com1.z0.glb.clouddn.com/upload-ueditor-image-20170913-1505316693215021744.jpg" title="http://7xo6kd.com1.z0.glb.clouddn.com/upload-ueditor-image-20170913-1505316693215021744.jpg" alt="timg (2).jpg"/>
				<p class="ImageCaption">引领年轻人的一种生活方式</p>
				</a>
			</div>
		</div>
		<p>LINE FRIENDS到底如何迅速发展的</p>
		<div class="Ingredients">
			<h3 class="SubHeader">发展方向</h3>
			<ol>
				<li>夸张的表情/li>
				<li>搞笑的动漫角色</li>
				<li>即时通讯服务</li>
				<li>生动的卡通形象</li>
				<li>植入知名韩剧</li>
				<li>与知名化妆品牌合作</li>
				<li>周边产品的颜值包装设计</li>
				<li>高质量产品</li>
				<li>不断提高知名度</li>
				<li>不断更新</li>
			</ol>
		</div>
		<div class="HowToMake">
			<h3 class="SubHeader">LINE FRIENDS到底如何迅速发展的</h3>
			<ol class="MethodWrapper">
				<li>将搞笑的动漫角色与免费信息通话服务完美的融合在一起</li>
				<li>动漫表情持续更新，已经发展出完整的系列</li>
				<li>植入知名韩剧，知名度持续爬升</li>
				<li>授权产品已经涵盖到生活的各个方面</li>
				<li>产品拥有高颜值的外表，而且具有实用性</li>
				<li>产品不仅有网上销售，而且开设了许多实体店</li>
				<li>有卡通形象延伸出咖啡厅、互动乐园、创意产品等</li>
			</ol>
		</div>
	</body>
</html>


<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 portfolio 的列出來-->
