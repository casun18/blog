---
title: test
tags: [test]
categories: []
date: 2024-06-28 01:22:53
description:
cover:
banner:
topic:
author:
references:
type: story
wiki: test
---
# 这是一个测试文档
## 主要是为了检测特性
{% quot Stellar 这是一个测试文档 %}
## 诗词节选
{% poetry 游山西村 author:陆游 footer:诗词节选 %}
莫笑农家腊酒浑，丰年留客足鸡豚。
**山重水复疑无路，柳暗花明又一村。**
箫鼓追随春社近，衣冠简朴古风存。
从今若许闲乘月，拄杖无时夜叩门。
{% endpoetry %}

## 文言文特性
{% paper style:underline title:文言文 author:诸葛亮 date:三国 footer:节选 %}
<!-- line left -->
出师表
<!-- paragraph -->
先帝创业未半而中道崩殂，今天下三分，益州疲弊，此诚危急存亡之秋也。然侍卫之臣不懈于内，忠志之士忘身于外者，盖追先帝之殊遇，欲报之于陛下也。诚宜开张圣听，以光先帝遗德，恢弘志士之气，不宜妄自菲薄，引喻失义，以塞忠谏之路也。
<!-- line right -->
后出师表
<!-- paragraph -->
先帝深虑汉、贼不两立，王业不偏安，故托臣以讨贼也。以先帝之明，量臣之才，固知臣伐贼，才弱敌强也。然不伐贼，王业亦亡。惟坐而待亡，孰与伐之？是故托臣而弗疑也。
{% endpaper %}

## 彩色备注块
{% note color:red 一共支持12种颜色，可以满足几乎所有的需求了。 color 可设置 red、orange、amber、yellow、green、cyan、blue、purple、light、dark、warning、error 几种取值。 %}

## 链接卡片
{% link https://xaoxuu.com/blog/20221029/ desc:true %}
